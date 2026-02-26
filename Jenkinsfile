pipeline {
    agent any

    triggers {
        //make an edit here !!! 
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
