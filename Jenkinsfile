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
                    bat "mvn clean install"
                }
                echo "-----Build Completed-----"
            }
        }
    }
}