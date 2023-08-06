pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'git@github.com:vinod2126/delete.git', branch: 'main', changelog: true, poll: true)
      }
    }

  }
}