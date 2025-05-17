pipeline {
    agent any

    tools {
        nodejs 'Node-24'    // Must match the name in Global Tool Config
        gradle 'abc'   // Must match the name in Global Tool Config
    }

    stages {
        stage('Check Node.js') {
            steps {
                sh 'echo "Node.js Version:"'
                sh 'node -v'
                sh 'echo "npm Version:"'
                sh 'npm -v'
            }
        }

        stage('Check Gradle') {
            steps {
                sh 'echo "Gradle Version:"'
                sh 'gradle -v'
            }
        }
    }
}
