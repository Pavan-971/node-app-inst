pipeline{
    agent any
    stages{
        stage("Getting code from repo")
        {
            steps{
                sh'git clone https://github.com/Pavan-971/node-app-inst.git'
                sh 'node node-app-inst/Web-app/server.js'
        
            }
        }
    }
}
