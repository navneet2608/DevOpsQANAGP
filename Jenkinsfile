CODE_CHANGES = getChanges()
pipeline{
    
    agent any
    
    tools{
        maven 'Maven'
    
    }
    
    stages{
        
    stage("code checkout"){
        steps{
            bat "echo hello"
        }
    }
        
    stage("code build"){
        steps{
        bat "mvn clean"
        }
    }
        
    stage("Unit Testing"){
        steps{
        bat "mvn test"
        }
    }
    }
        
        post{
            success{
                bat "echo success"
            }
    }
}
