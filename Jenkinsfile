pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Checkout Completed Successfully."
            }
        }
        stage('Build') {
            steps {
                echo "-----Initializing Build-----"
                dir("helloworld") {
                    bat "C:\\apache-maven-3.6.3\\bin\\mvn clean install"
                }
                echo "-----Build Completed-----"
            }
        }
    }
}