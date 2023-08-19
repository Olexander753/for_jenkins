pipeline {
    agent {
        docker { image 'node:18.17.1-alpine3.18' }
    }
    stage('Docker') {
            steps {
                sh 'node --version'
            }
        }
   }
}
