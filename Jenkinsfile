pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                git branch: 'main', url: 'https://github.com/rejunrajreju/pipeline-nextjs-test.git'
                sh 'npm install'
                sh 'npm run build'
            }
        }
        stage('Test') { 
            steps {
                echo "test"
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploy"
            }
        }
    }
}