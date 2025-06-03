pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
                cleanWs()
            }
        }
        
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean install'
            }
        }
    }

}
