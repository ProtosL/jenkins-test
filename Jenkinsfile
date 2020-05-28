pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                cd './my-app'
                npm install &&
                npm run build
                echo 'Hello world'
		        echo 'Hello jenkins'
            }
        }
    }
}
