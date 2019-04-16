pipeline {
    agent {
        docker {
            sudo image 'node:6-alpine' 
            sudo args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh ' sudo npm install' 
            }
        }
    }
}
