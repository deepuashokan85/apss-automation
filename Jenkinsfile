pipeline {
  agent any

  stages {
    stage('build') {
      steps {
        sh 'echo Step 1'
        sh 'echo step 2'
        sh 'echo step 3'
      }
    }
    stage('run') {
      steps {
        sh 'echo Pradeep Kumar A'
      }
    }
  }
  post {
    success {
      archiveArtifacts artifacts: 'rectangle.jar', fingerprint: true
    }
  }
}
