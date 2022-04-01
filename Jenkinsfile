pipeline {
    agent any 
    stages {
        stage('clean and clean') { 
            steps {
                bat "mvn clean"
                bat "echo 'qwerty'"
            }
        }
        stage('test') { 
            steps {
                bat "mvn test"
            }
        }
        stage('Package') { 
            steps {
                bat "mvn package"
            }
        }
    }
}
