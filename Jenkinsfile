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
                echo 'Running a simple test script...'
                sh '''
                    echo "Hello from Jenkins Pipeline!"
                    echo "GitHub integration works!"
                '''
            }
        }
    }
}

