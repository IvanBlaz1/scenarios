pipeline {
    agent any

    stages {
        stage('Run Football Scenario') {
            steps {
                //wrap([$class: 'Xvfb']) {
                // Combine all commands in a single shell step
                sh '''
                    /home/ivanb/run.sh
                '''
                //}
            }
        }
    }
}
