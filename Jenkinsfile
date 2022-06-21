pipeline {
    agent any
        stages {
            stage('get_code_message') {
                steps {
                    sh 'echo "Getting code from GitHub"'
                }
            }
            stage('getting_code') {
                sh 'git clone https://github.com/Awan/cfg.git'
            }
        }
}











// vim: set ft=groovy :
