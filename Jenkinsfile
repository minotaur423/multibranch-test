pipeline{
  agent any
  stages{
    stage('Branch test'){
      steps{
        echo "This branch is ${env.BRANCH_NAME}"
        echo "BUILD_NUMBER is ${env.BUILD_NUMBER}"
        echo "BUILD_ID is ${env.BUILD_ID}"
        echo "BUILD_DISPLAY_NAME is ${env.BUILD_DISPLAY_NAME}"
        echo "JOB_NAME is ${env.JOB_NAME}"
        echo "JOB_BASE_NAME is ${env.JOB_BASE_NAME}"
        echo "BUILD_TAG is ${env.BUILD_TAG}"
        echo "EXECUTOR_NUMBER is ${env.EXECUTOR_NUMBER}"
        echo "NODE_NAME is ${env.NODE_NAME}"
        echo "NODE_LABELS is ${env.NODE_LABELS}"
        echo "WORKSPACE is ${env.WORKSPACE}"
        echo "JENKINS_HOME is ${env.JENKINS_HOME}"
        echo "JENKINS_URL is ${env.JENKINS_URL}"
        echo "BUILD_URL is ${env.BUILD_URL}"
        echo "JOB_URL is ${env.JOB_URL}"
        echo "CHANGE_ID is ${env.CHANGE_ID}"
      }
    }
  }
}
