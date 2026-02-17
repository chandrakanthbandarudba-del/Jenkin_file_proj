pipeline {
    agent any

    tools {
        maven 'maven-3'
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/your-repo/maven-project.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
