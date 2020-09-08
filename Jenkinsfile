//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { D3 { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
