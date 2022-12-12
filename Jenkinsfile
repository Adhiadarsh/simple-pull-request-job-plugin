pipeline{
    agent any
        stages {
                stage('One'){
                        steps{
                               sh "echo step1 is executed"
                        }
                }
                stage('Two'){
                        steps{
                                input('Do you want to proced?')
                        }
                }
                stage('Three'){
                    steps{
                            sh "echo  after permison step3 is executed"
                    }
                }
                stage('Four'){
                    steps{
                               sh "echo final foutth steps is succesful" 
                        }
                }
        }        
}
