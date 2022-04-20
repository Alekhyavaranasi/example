pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh "python hello.py"
            }
     
        }
        stage('Deploy') {
            steps {
                echo "Deploying...."
            }
        }
    }
}
