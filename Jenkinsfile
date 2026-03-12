pipeline {
    agent any
    tools {
        maven 'M3' // Use the exact name you specified in Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
