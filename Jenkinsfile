pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Thiru1807/Jenkins_Demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed'
            }
        }
    }
}
