pipeline {
    agent {
        docker {
            image 'centos'
            label 'generic'
        }
    } //agent
    stages {
        stage("Check hostname of docker container"){
            steps {
                sh """
                    cat /etc/hostname
                """
            } // staeps
        } // stage

    } // stages
}