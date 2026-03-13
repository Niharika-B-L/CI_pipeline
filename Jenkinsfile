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

        

    }

