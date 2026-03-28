pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac App.java'
            }
        }

        stage('Run') {
            steps {
                bat 'echo 5 | java App'
            }
        }
    }
}
