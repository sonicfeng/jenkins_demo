pipeline {
  agent none
  stages {
    stage('Deploy') {
      agent any
      steps {
        echo 'Deploying testing'
        sh './deploy_jenkins.sh'
      }
    }
  }
}
