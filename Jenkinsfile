pipeline {

  agent {
    label 'jenkins-jnlp-agent'
  }

  stages {
    stage('Display test') {
      steps {
        sh returnStdout: true, script: ls -l
      }
    }
  }

}
