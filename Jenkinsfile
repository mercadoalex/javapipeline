pipeline {
    agent { docker { image 'openjdk' } }
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
