pipeline{
    agent any
    stages{
        stage("Getting code from repo")
        {
            steps{
                sh 'rm -rf node-app-inst '
                sh'git clone https://github.com/Pavan-971/node-app-inst.git'
                
                sh 'bash noderestart.sh'
                sh 'node node-app-inst/Web-app/server.js'
                sh 'ok'
        
            }
        }
    }
}
