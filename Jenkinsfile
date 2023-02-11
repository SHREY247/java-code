pipeline {
    agent any

    stages {
        stage('GIT CHECKOUT') {
            steps {
                git branch: 'main', url: 'https://github.com/vishalchauhan91196/java-code.git'
            }
        }

        stage('UNIT TESTING') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
