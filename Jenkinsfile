pipeline{
  agent any

  tools{
    nodejs 'nodejs-22-6-0'
  }
  stages{
          stage('Installing Dependencies'){
              steps{
                    script{
                    sh '''
                      npm install --no-audit
                    '''
                }
            }
        }
  }

}
