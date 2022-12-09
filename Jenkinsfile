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
                    
                    parallel {
                                    stage('Unit Test'){
                                                     steps{
                                                             echo "Running the unit test.."
                                                     } 
                                   }
                    }
                       
                }
               
                stage('Four'){
                        steps{
                               sh "echo step 4" 
                        }
                }
           
            
            }    
            
        }
              
}
