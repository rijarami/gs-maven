pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                bat 'cd complete'
                bat 'mvn package'
            }
        }
    }
}
