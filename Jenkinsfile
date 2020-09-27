pipeline {
    agent any

    stages {
        stage('Maven Compile') {
            steps {
                    echo 'Project compile stage'
                    bat label: 'Compilation running', script: '''mvn compile'''
                
            }
}

stage('Unit Test') {
            steps {
                    echo 'Project Testing stage'
                    bat label: 'Test running', script: '''mvn test'''
                
            }
}

stage('Maven Package') {
            steps {
                    echo 'Project pacakaging stage'
                    bat label: 'Project running', script: '''mvn package'''
                
            }
}
}}