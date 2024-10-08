pipeline {
    agent any
    stages {
        stage('code checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/javahometech/ai-leads/'
            }
        }
        stage('maven build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
