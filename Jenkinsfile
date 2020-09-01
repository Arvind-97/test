pipeline {
    agent any
    stages {
        stage('Compile Stage') {
            steps {
                withMaven(maven : 'maven-3_3_9') {
                    sh 'mvn clean compile'
                }
                //
            }
        }
        stage('Testing Stage') {
            steps {
                 withMaven(maven : 'maven-3_3_9') {
                    sh 'mvn test'
                 }
                //
            }
        }
        stage('Deployment Stage') {
            steps {
                withMaven(maven : 'maven-3_3_9') {
                    sh 'mvn deploy'
                }
                //
            }
        }
    }
}
