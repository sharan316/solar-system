pipeline{
  agent any

  tools{
    nodejs 'nodejs-22-6-0'
  }
  stages{
          stage('Node Version'){
              steps{
                    script{
                    sh '''
                      node -v
                      npm -v

                    '''
                }
            }
        }
  }

}
