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
        sh '''su root
apt install tree -y

echo \'run the jenkins\' > /home/ubunut/test.sh'''
      }
    }

  }
  environment {
    GITHUB_TOKEN = credentials('github')
  }
}