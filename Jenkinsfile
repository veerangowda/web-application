pipeline {
agent any
stages {
  stage('print') {
    steps {
      sh 'echo Hello World'
    }
  }
stage('git clone') {
steps {
git 'https://github.com/veerangowda/web-application'
}
}
  stage('python') {
    steps {
      sh 'cat helo.py'
    }
  }
}
}

