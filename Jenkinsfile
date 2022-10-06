pipeline {
  agent {
    label 'windows'
  }
  stages {
    stage ('gitcheckout') {
      steps {
        git 'https://github.com/GARAGANAGARAJU/jenkins_pipeline.git'
      }
    }
    stage ('build') {
      steps {
        echo 'build'
      }
    }
  }
}
