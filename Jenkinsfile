pipeline{
    
    agent any
    
    stages{
        
    stage("code checkout"){
        steps{
            system.out.println("Hello")
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
