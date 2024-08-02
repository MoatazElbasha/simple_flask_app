pipeline {
    agent any
    
    stages {
        stage('running security tests on the application') {
            steps {
                clamscan Dockerfile
            }
        }
    
        stage('creating image from the applicatio') {
            steps {
                sh "docker build -t new_app ."
            }
        }
    
        stage('running security scans on the image') {
            steps {
                echo "m"
            }
        }
        
        stage('uploading the image on docker hub') {
            steps {
                echo "m"
            }
        }
    }
}
