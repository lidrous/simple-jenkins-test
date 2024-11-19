pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning the repository...'
                checkout scm
            }
        }

        stage('Run Script') {
            steps {
                sh '''
                    echo "Hello from Jenkins Pipeline!"
                    echo "Testing GitHub Integration"
                '''
            }
        }
    }
}
