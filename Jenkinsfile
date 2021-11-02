pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package -f ./simple-java-maven-app-master/pom.xml' 
            }
        }
    }
}
