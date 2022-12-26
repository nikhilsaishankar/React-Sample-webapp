pipeline {
    agent any
    stages {
        stage('Check branch') { 
            steps {
                sh 'git branch'
            }
        }
            stage('Build') { 
            steps {
                sh 'npm install' 
                sh 'npm run build'
                echo "working fine"
            }
        }
    }
}
