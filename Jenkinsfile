pipeline {
    agent any
    stages {
        stage('gesture') {
            steps {
                echo 'Hello World!'
            }
        }
        stage('cloning') {
            steps {
                git branch: 'main', url: 'https://github.com/Shin-chin-Lili/jenkinsfile_test.git'
            }
        }
    }
}
