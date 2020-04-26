pipeline {
    agent none 
    stages {
        stage('Example Build') {
            agent any 
            steps {
                echo 'Hello, Maven'
            }
        }
        stage('Example Test') {
            agent any 
            steps {
                echo 'Hello, JDK'
            }
        }
    }
}
