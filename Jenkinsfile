pipeline {
  agent any
      environment {
        GITHUB_TOKEN = credentials('github') // Use the correct ID of the token credential
    }
  stages {
    stage('git') {
      steps {
        git(url: 'git@github.com:vinod2126/delete.git', branch: 'main')
      }
    }

  }
}
