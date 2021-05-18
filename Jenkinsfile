pipeline {
    agent any
    stages {

    stage('Clone repository') {
        /* Cloning the Repository to our Workspace */

        checkout scm
    }

    stage('Build image') {
        /* This builds the actual image */

        sh 'podman build -t ssm123/app .'
    }

    

	
    stage('Push image') {
        
    }
}
}
