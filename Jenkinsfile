pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/javahometech/ai-leads/'
            }
        }
        stage('Hello') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
