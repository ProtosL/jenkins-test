pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
                echo 'Hello world'
		        echo 'Hello jenkins'
            }
        }
    }
}
