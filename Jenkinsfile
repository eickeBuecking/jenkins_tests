pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('Build') {
            steps {
                sh -c 'echo "Hello World"'
                sh -c '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
