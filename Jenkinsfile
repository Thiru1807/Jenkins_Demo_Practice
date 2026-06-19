pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Thiru1807/Jenkins_Demo_Practice.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed'
            }
        }
    }
}
