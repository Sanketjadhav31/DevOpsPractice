pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                // This checks out the code from the specified Git repository and branch.
                git url: 'https://github.com/Sanketjadhav31/Devops.git', branch: 'master'
            }
        }
        stage('Build') {
            steps {
                // Replace this with your actual build commands.
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                // Replace this with your actual testing commands.
                echo 'Test'
            }
        }
        stage('Deploy') {
            steps {
                // Replace this with your deployment commands.
                echo 'Deploy'
            }
        }
    }
}
