pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                build job: "multi2/master"
            }
        }
    }
}
