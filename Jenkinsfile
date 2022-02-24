pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                echo 'Build automation is Running'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'

            }
        }
    }
}
