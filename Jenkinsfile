pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/Abdal2006/devops-project-2.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

        stage('Run') {
            steps {
                sh 'java -cp target/hello-app-1.0-SNAPSHOT.jar com.example.App'
            }
        }

    }
}
