pipline{
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
            
        }
              
}
