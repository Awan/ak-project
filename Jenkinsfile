pipeline {
    agent any
        stages {
            stage('get_code_message') {
                steps {
                    sh 'echo "Getting code from GitHub"'
                    sh 'git clone https://github.com/Awan/cfg.git'
                }
            }
        }
    post {
        failure {
            sh 'cd cfg'
            sh 'git pull origin master'
        }
    }
}












// vim: set ft=groovy :
