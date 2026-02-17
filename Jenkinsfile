pipeline {
    agent any

   tools {
       maven 'maven-3'
   }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/chandrakanthbandarudba-del/Jenkin_file_proj.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
