pipeline {
    agent {
        docker {
            image 'python'
            label 'generic'
        }
    } //agent
    stages {
        stage("Run hello world"){
            steps {
                sh """
                    python hello.py
                """
            } // staeps
        } // stage

    } // stages
}