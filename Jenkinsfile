pipeline {
    agent any {
        stages {
            stage("hostname"){
                steps {
                    sh 'hostname'
                }
            }
            stage("memory"){
                steps {
                    sh 'free -h'
                }
            }
            stage("disk"){
                steps {
                    sh 'df -kh'
                }
            }
            stage("cpu"){
                steps {
                    sh 'lscpu'
                }
            }
        }
    }
}
