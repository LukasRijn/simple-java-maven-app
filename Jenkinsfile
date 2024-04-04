pipeline {
    agent any
    tools {
        maven 'packerMaven'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
   
}
