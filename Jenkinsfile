pipeline {

    agent any

    
    stages {
         stage('build') {
          steps {
              sh 'npm install'
            }
          }

        stage('start') {
            steps {
                sh 'echo npm start'
            }
        }
        
        stage('Test') {
            steps {
               
                    sh "echo sudo-npm-test"
                
            }
        }
        
        stage('Docker Comopse Up') {
            steps {
               
                    sh "echo sudo-docker-compose-up"
                
            }
        }
         stage('kill') {
            steps {
               
                    sh "echo sudo-docker-compose-down"
                
            }
        }
    }
}
