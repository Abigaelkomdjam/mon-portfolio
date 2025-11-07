pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                // Jenkins automatically clones the code when the pipeline starts
                // from the configured repository and branch.
                // This stage is implicitly handled but good to visualize.
                echo 'Cloning the repository....'
               // git branch: 'dev', url: 'YOUR_GITHUB_REPOSITORY_URL'
            }
        }
        stage('Build') {
            steps {
                // The commands here depend on your project.
                // For a Java project, you might run: sh 'mvn clean install'
                // For a Node.js project, you might run: sh 'npm install'
                echo 'Building the application...'
                // Add your build commands here
            }
        }
        stage('Deploy') {
            steps {
                // The commands here depend on your deployment target.
                // You might copy files to a server or push a Docker image.
                echo 'Deploying the application....'
                // Add your deployment commands here
            }
        }
    }
}