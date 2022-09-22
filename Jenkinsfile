pipeline {
    agent any

    stages {
        stage('Source') {
            steps {
                git 'https://github.com/shanthshivam/SpringMysqlDemo.git'
            }
        }
        
        stage('Build'){
            steps{
                echo 'mvn clean package'
            }
        }
    }
}


