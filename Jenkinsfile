pipeline {
    agent any

    tools {
        nodejs 'nodejs-18'
        gradle 'gradle-7.6'
    }

    stages {
        stage('Check Tools') {
            steps {
                sh 'node -v'
                sh 'npm -v'
                sh 'gradle -v'
            }
        }
    }
}
