pipline{
    agent any
        stages {
                stage('One'){
                        steps{
                                sh label: '', script: 'echo "hi"'
                        }
                }
                stage('Two'){
                        steps{
                                input('Do you want to proced?')
                        }
                }
            
        }
              
}
