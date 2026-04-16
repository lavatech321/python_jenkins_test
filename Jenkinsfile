pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('Job1') {
            steps {
               sh '''
               echo 'Hello World1'
               mkdir '/tmp/abc'
               '''
            }
        }
        stage('Job2') {
            steps {
                echo 'Hello World2'
                
            }
        }
        stage('Job3') {
            steps {
                echo 'Hello World3'
            }
        }
    }
}
