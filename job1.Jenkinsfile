node('docker') {
    checkout D:\work\jenkinsJobs\job1
    stage('Build') {
        docker.image('python:3.5.1').inside {
            sh 'python --version'
        }
    }
}