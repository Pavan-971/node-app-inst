pipeline{
    agent any
    stages{
        stage("Getting code from repo")
        {
            steps{
                
                sh'git clone https://github.com/Pavan-971/node-app-inst.git'
                
                sh 'bash noderestart.sh'
                sh 'cp -R node-app-inst /home/ec2-user/'
                sh 'node /home/ec2-user/node-app-inst/node-app-inst/server.js'
        
            }
        }
    }
}
