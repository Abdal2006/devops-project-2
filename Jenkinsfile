pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'mvn clean package'
            }
        }

        stage('Run') {
            steps {
                echo 'Running app...'
                sh 'java -cp target/hello-app-1.0-SNAPSHOT.jar com.example.App'
            }
        }
    }
}
