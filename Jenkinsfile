pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('clone-build') {
      steps {
        git(branch: 'master', url: 'https://github.com/saravanak1900/demo-training.git')
      }
    }

  }
}