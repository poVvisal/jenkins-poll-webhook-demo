pipeline {
    agent any

    triggers {
        
        pollSCM('H/2 * * * *') 
    }

    stages {
        stage('Build') {
            steps {
                echo "Build stage running"
            }
        }
    }
}
