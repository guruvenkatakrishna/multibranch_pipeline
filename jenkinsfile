pipeline {
    agent any
    environment {
        // Define environment variables here
        BRANCH_NAME = "${env.BRANCH_NAME}"
    }
    stages {
        stage('Git CHECKOUT Stage') {
            steps {
                echo 'this is git checkout stage'
            }
        }
        stage('BUILD Stage') {
            steps {
                echo 'this is git Build Stage'
            }
        }
        stage('Git TEST Stage') {
            steps {
                echo 'this is git TEST stagee'
            }
        }
        stage('Git PUSH Stage') {
            steps {
               echo 'this is git PUSH stage'
                   }
        }
    }
}
