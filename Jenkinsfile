pipeline {
  agent any
  stages {
    stage('build project') {
      steps {
        build(job: 'mytestbuildjob', quietPeriod: 1, wait: true)
      }
    }
  }
}