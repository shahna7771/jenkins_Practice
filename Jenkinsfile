
pipeline{
    agent any
        stages{
            stage('build'){
                agent{
                    docker{
                        image 'node:18-alpine'
                        reuseNode true
                    }
                }

                steps{
                    sh '''
                    ls -l
                    '''
                }
            }
        }
    
}