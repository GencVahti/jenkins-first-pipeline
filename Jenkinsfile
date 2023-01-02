pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Hello World, this is build-2!'
            }
        }
        stage('push') {
            steps {
                echo 'Hello World, this is push-2!'
            }
        }
        stage('deploy') {
            steps {
                echo 'Hello World, this is deploy-2!'
            }
        }
        stage('run') {
            steps {
                echo 'This is pyhton file with trigger!!!'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }    
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }    
    }
}
