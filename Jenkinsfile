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
                        when {
                                not {
                                    branch "master"
                                }
                        }
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
                                    agent {
                                        docker {
                                                reuseNode  false
                                                image 'ubuntu'
                                        }
                                    }
                                    steps {
                                        echo 'Running the integration test..'
                                    }
                                
                                
                }
            }
        }
}
}
