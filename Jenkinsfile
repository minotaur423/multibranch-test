pipeline{
  agent any
  stages{
    stage('Branch test'){
      steps{
        echo "This branch is ${env.BRANCH_NAME} and the this commit is ${env.GIT_COMMIT}"
      }
    }
  }
}
