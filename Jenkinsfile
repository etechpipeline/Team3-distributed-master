pipeline{
    agent {
        label {
            label "slave1"
        }
    }
    stages {
        stage('codeCheckout') {
            steps {
                git branch: 'main', credentialsId: '27ad29e6-be3a-49fa-8285-afa75c144e11', url: 'https://github.com/etechpipeline/Team3-distributed-master.git'
            }
        }
        stage('Anny-push-to-slave1') {
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
        stage('Inno-push-to-slave2') {
            agent {
                label {
                    label "slave2"
                }
            }
            steps {
                echo 'Happy Father Day to all the Fathers!'
            }
        }
        stage('emmanuel-push-to-slave3'){
            agent {
                label {
                    label "slave3"
                }
            }
            steps {
                echo 'Happy Father Day to all the Fathers!'
            }
        }                        
    }    
}    