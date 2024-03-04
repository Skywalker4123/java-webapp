pipeline {
    agent any

    stages {
        stage('Git SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/Skywalker4123/java-webapp.git'
            }
        }
        stage('Maven Test') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
