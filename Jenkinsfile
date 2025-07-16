pipeline {
    agent any

    stages {
        stage('Code') {
            steps {
                echo '📥 Cloning repo...'
                git 'https://github.com/Parvane-gith/jenkins-static-site.git'
            }
        }
        stage('Build') {
            steps {
                echo '🔧 Listing project files...'
                sh 'ls -la'
            }
        }
        stage('Deploy') {
            steps {
                echo '🚀 Previewing index.html'
                sh 'cat index.html'
            }
        }
    }
}
