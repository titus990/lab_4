pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from GitHub...'
                // Jenkins handles the actual 'git checkout' automatically when using "Pipeline script from SCM"
            }
        }
        stage('Deploy (simulated)') {
            steps {
                echo 'Simulating deployment of the HTML file...'
                // You could add steps here later to copy the file to a web server
            }
        }
    }
}