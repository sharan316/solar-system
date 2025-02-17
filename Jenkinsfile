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
          stage('Dependency Audit Stage'){
                steps{
                      script{
                      sh '''
                        npm audit --audit-level=critical

                      '''
                  }
              }
          }
        
  }

}
