pipeline {
  agent any
  stages {
    stage('Build') {
      when {
        buildingTag()
      }
      steps {
        echo 'Building tag test line'
      }
    }
  }
}
