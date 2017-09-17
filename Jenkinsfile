pipeline {
  agent any
  stages {
    stage('Bundle It Up') {
      steps {
        git(url: 'https://github.com/rajdhandus/maven-project.git', branch: '*/master', changelog: true, poll: true)
      }
    }
  }
}