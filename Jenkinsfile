pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/vinod2126/delete.git', branch: 'main')
      }
    }

  }
  environment {
    GITHUB_TOKEN = credentials('github')
  }
}