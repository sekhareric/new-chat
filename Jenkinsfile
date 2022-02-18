pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi') {
            steps {
                echo 'How are you...!'
            }
        }
        stage('SCM') {
            steps {
                git branch: 'dev', url: 'https://github.com/sekhareric/new-chat.git'
            }
        }
        stage('bye') {
            steps {
                echo 'bye guys...!'
            }
        }
    }
}
