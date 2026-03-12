

pipeline {
    agent {
        label 'Master-New'
          }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
