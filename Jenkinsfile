properties([pipelineTriggers([githubPush()])])
node('linux') {
    git url: 'https://github.com/MeeraReddy/trial.git', branch: 'master'
    stage('Test') {
        sh "env"
    }
}
