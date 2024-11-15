pipeline
{
  agent any
  {
    stages{
      stage('testing')
            {
              script {
                    // Apply Terraform changes based on the branch
                    if (env.BRANCH_NAME == 'master') {
                        sh 'touch rana'
                    } else if (env.BRANCH_NAME == 'test1') {
                        sh 'touch vikas'
                    } else if (env.BRANCH_NAME == 'test2') {
                        sh 'touch ravi'
                    }
                }
            }
              }
            }
    }
  }
}
