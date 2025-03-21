pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', credentialsId: 'GitHub_Credentials', url: 'https://github.com/ranjanisengottaian/ranjani-task.git'  }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
