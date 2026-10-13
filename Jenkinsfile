<<<<<<< HEAD
=======

>>>>>>> 22003a2f817d3664ea9f20c52e61fef487c85d90
pipeline {
    agent any

    stages {
<<<<<<< HEAD

=======
>>>>>>> 22003a2f817d3664ea9f20c52e61fef487c85d90
        stage('Build') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Test') {
            steps {
                bat 'java HelloWorld'
            }
        }

        stage('Archive') {
            steps {
                archiveArtifacts artifacts: '*.class', fingerprint: true
            }
        }
    }
<<<<<<< HEAD
}
=======
}
>>>>>>> 22003a2f817d3664ea9f20c52e61fef487c85d90
