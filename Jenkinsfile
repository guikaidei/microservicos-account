pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'rm -rf target'
                sh 'mvn -B -DskipTests clean install'
            }
        }
    }

}
