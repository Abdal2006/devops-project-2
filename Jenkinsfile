<<<<<<< HEAD
node {
    stage('Build') {
        sh '/opt/homebrew/bin/mvn clean package'
    }

    stage('Run') {
        sh 'java -cp target/hello-app-1.0-SNAPSHOT.jar com.example.App'
    }
}pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '/opt/homebrew/bin/mvn clean package'
            }
        }

        stage('Run') {
            steps {
                sh 'java -cp target/hello-app-1.0-SNAPSHOT.jar com.example.App'
            }
        }
    }
}node {

    stage('Build') {
        sh '/opt/homebrew/bin/mvn clean package'
    }

    stage('Run') {
        sh 'java -cp target/hello-app-1.0-SNAPSHOT.jar com.example.App'
    }
}pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh '/opt/homebrew/bin/mvn clean package'
            }
        }

        stage('Run') {
            steps {
                sh 'java -cp target/hello-app-1.0-SNAPSHOT.jar com.example.App'
            }
        }
    }
}pipeline {
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
=======
stage('Build') {
    steps {
        sh 'ls -al'
        sh 'cd devops-project-2 && mvn clean package'
>>>>>>> b4b8d33 (fix pom path issue)
    }
}
