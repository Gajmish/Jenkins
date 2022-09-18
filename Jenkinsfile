pipeline {
    agent any 
    stages {
        stage('df -h') {
            steps {
                echo 'stage one'
                sh 'df -h'
            }
        }
        stage('lsblk') {
            steps {
                echo 'stage2'
                sh 'lsblk'
            }
        }
    }
}
