#pipeline {
#    agent any
#    stages {
#        stage('build') {
#            steps {
#                echo "Hello This is my first jenkins pipeline"
#                sh 'echo using shell within Jenkinsfile'
#                echo 'not using shell in the Jenkinsfile'
#            }
#        }
#    }
#}


pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Hello World, this is build!'
            }
        }
        stage('push') {
            steps {
                echo 'Hello World, this is push!'
            }
        }
        stage('deploy') {
            steps {
                echo 'Hello World, this is deploy!'
            }
        }
    }
}
