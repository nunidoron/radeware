properties([pipelineTriggers([pollSCM('* * * * *')])])
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
