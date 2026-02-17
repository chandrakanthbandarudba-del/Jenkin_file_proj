pipeline {
    agent any

   tools {
       maven 'maven-3'
   }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/chandrakanthbandarudba-del/Jenkin_file_proj.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
