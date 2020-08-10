pipeline {
    agent {
        docker { image 'maven' }
    }
    stages {
        stage('build') {
            steps {
               mvn package
            }
        }
    }
}
