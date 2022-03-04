pipeline {
    agent any
    tools { nodejs "node" }
    stages {
        stage('Build') {
            steps {
                echo "building npm website"
                sh "npm install"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploying wbste"
                sh "npm start"
            }
        }
    }
}
