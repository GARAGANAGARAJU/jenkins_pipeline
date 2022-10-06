pipeline {
  agent {
    label 'windows'
  }
  stages {
    stage ('gitcheckout') {
      steps {
        git branch: 'main', url: 'https://github.com/GARAGANAGARAJU/spring-petclinic.git'
      }
    }
    stage ('build') {
      steps {
        echo 'build'
      }
    }
  }
