pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // This checks out the code from the repository.
                git(url: 'https://github.com/Shakedkdoshim/GIT.git', branch: 'main')
            }
        }
        stage('Run Script') {
            steps {
                    echo "Running myapp.py on master branch..."
                    sh 'python3 main.py'
                }
            }

