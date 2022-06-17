pipeline{
    agent {
        label {
            label "slave1"
        }
    }
    stages {
        stage('codeCheckout') {
            steps {
                Githubcode
            }
        }
        stage('Anny-push-to-slave1') {
            stage('push-to-slave1') {
                agent {
                    label {
                        label "slave1"
                    }
                }
                steps{
                    sh 'df -h'
                    echo 'Have a lovely day!'
                }
            }
        }
    }
}