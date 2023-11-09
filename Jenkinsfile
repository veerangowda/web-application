pipeline {
agent any
tools {
maven 'maven'
}
stages {
  stage('print') {
    steps {
      sh 'echo 'Hello World'
    }
  }
stage('git clone') {
steps {
git 'https://github.com/veerangowda/web-application'
}
}
stage('validate') {
steps {
sh 'mvn validate'
}
}
stage('compile') {
steps {
sh 'mvn compile'
}
}
stage('package') {
steps {
sh 'mvn package'
}
}
}
}

