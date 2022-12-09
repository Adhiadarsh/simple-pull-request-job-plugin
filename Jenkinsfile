pipline{
    agent any
        stages {
                stage('One'){
                        steps{
                                echo 'hi,this is Zulatkha from edureka'
                        }
                }
                stage('Two'){
                        steps{
                                input('Do you want to proced?')
                        }
                }
                stage('Three'){
                      
                       
                        steps{
                            echo "Hello"
                        }
                }
                stage('Four') {
                                parallel {
                                    stage('Unit Test'){
                                                     steps{
                                                             echo "Running the unit test.."
                                       }
                }
                stage('Integration test') {
                                    
                                    }
                                    steps {
                                        echo 'Running the integration test..'
                                    }
                                
                                
                }
            }
        }
}
}
