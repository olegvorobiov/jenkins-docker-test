pipeline {
    agent {
        dockerfile true
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