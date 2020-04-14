pipeline {
    agent {
        dockerfile {
            label 'generic'
        }
    } //agent
    stages {
        stage("Run hello world"){
            steps {
                sh """
                    python requestgoogle.py
                """
            } // staeps
        } // stage

    } // stages
}