pipeline {
    agent {
        docker { image 'node:18.17.1-alpine3.18' }
    }
     stages {
     stage('Build') {
       steps {
         sh 'python time.py'
       }
     }

     stage('Test') {
       steps {
         echo 'Testing'
       }
     }

     stage('Deploy') {
       steps {
         echo 'Deploying'
       }
     }

    stage('Docker') {
            steps {
                sh 'node --version'
            }
        }
   }
}
