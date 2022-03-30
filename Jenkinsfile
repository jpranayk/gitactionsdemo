pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                checkout scm
            }
        }
          stage('demo multiple commands') {
            steps {
                sh '''
                uname -a 
                 env
                ifconfig
                ''' 
            }
        }
      stage('demo shellscript') {
            steps {
                sh './hello.sh'
            }
        }
    }
}
