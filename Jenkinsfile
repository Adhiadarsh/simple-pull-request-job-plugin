pipeline{
    agent any
        stages {
                stage('One'){
                        steps{
                               sh "echo step 1"
                        }
                }
                stage('Two'){
                        steps{
                                input('Do you want to proced?')
                        }
                }
                
                stage('Three'){
                        steps{
                               sh "echo step 3" 
                        }
                }
               
                stage('Four'){
                        steps{
                               sh "echo step 4" 
                        }
                }
            
            
        }
              
}
