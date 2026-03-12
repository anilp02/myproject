

pipeline {
    agent {
        label 'Master-new'
          }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
