
pipeline {
    agent any
    
    options { skipDefaultCheckout() }

    stages {

        
        stage('build') {
            steps {
                    sh 'echo hey this is echood from jenkins'
                    sh 'mvn --version'
                }
            }
        }
}