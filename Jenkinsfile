pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/vinod2126/delete.git', branch: 'main')
      }
    }

    stage('shell') {
      steps {
        sh '''

ls -al'''
      }
    }

  }
  environment {
    GITHUB_TOKEN = credentials('github')
  }
}