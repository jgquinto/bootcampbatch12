pipeline {
    agent any
    triggers {
        cron('30 */4 * * 1-5')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
