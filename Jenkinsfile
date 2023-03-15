properties([parameters([string(description: 'Please add the file path', name: 'path')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Goging to execute the script path: [${path}]"
            }
        }
    }
}
