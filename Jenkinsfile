pipeline {
    agent any

    stages {
        stage('Build Stage') {
            steps {
                echo "THis is Build Stage"
                sh 'sleep 5'             
            }
        }
        stage('Push Stage') {
            steps {
                echo 'This is Push Stage'
                sh 'sleep 5'
            }
        }
        stage('Deploy Stage') {
            steps {
                echo 'This is Deploy Stage'
                sh 'sleep 5'
            }
        }
    }
}    
