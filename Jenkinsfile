pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                build job: "muilti2/master"
            }
        }
    }
}
