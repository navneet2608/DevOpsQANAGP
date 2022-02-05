pipeline{
    
    agent any
    
    stages{
        
    stage("code checkout"){
        steps{
            bat "echo hello"
        }
    }
        
    stage("code build"){
        steps{
        bat "echo build"
        }
    }
        
    stage("Unit Testing"){
        steps{
        bat "echo unit"
        }
    }
    }
        
        post{
            success{
                bat "echo success"
            }
    }
}
