pipeline {
    agent any

    stages {
        stage('Source') {
            steps {
                git 'https://github.com/SushmithaNayak23/SpringMysqlDemo.git'
            }
        }
        
        stage('Build'){
            steps{
                echo 'mvn clean package'
            }
        }
    }
}


