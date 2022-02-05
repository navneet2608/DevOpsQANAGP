pipeline{
    
    agent any
    
    stages{
        
    stage("code checkout"){
        steps{
            sh "echo hello"
        }
    }
        
    stage("code build"){
        steps{
        sh "echo build"
        }
    }
        
    stage("Unit Testing"){
        steps{
        sh "echo unit"
        }
    }
    }
        
        post{
            success{
                sh "echo success"
            }
    }
}
