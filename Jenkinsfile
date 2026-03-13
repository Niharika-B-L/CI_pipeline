pipeline {
    agent any

    stages {

        stage('Compile Java Program') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run Java Program') {
            steps {
                bat 'java HelloWorld'
            }
        }

        stage('Archive Artifacts') {
            steps {
                archiveArtifacts artifacts: '*.class', fingerprint: true
            }
        }

    }
}
