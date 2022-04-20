pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh "javac HelloWorld.java"
            }
        }
        stage('Execute') {
            steps {
                 echo "Executing.."
                sh "java HelloWorld"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying...."
            }
        }
    }
}