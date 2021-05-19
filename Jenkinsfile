pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                echo 'Compilando el Java'
                sh javac HolaMundo.java
            }
        }
        stage('Running....') {
            steps {
                echo 'Ejecutando el Java'
                sh java HolaMundo.class
            }
        }
       stage('Artifact') {
            steps {
                echo 'HAcemos el distribuble'
                sh javac HolaMundo.java
            }
        } 
    }
}
