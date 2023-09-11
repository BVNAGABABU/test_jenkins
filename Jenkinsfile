pipeline {
  agent any 
  stages {
    stage('Build Master') {
      when {
        branch 'main'
      }
      steps {
        echo 'Building production'
      }
    }

    stage('Build dev') {
      when {
        branch 'master'
      }
      steps {
        echo 'Building dev'
      }
    }
  }
}
