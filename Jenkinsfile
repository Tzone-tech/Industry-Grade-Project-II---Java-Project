pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'compiling..'
                sh 'mvn compile'
            }
        }

        stage('test') {
            steps {
                echo 'Testing....'
                sh 'mvn test'
            }
        }

        stage('package') {
            steps {
                echo 'testing....'
                sh 'mvn package'
            }
        }
    }
}