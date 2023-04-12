pipeline {
  agent any
  stages{
    stage('check'){
      steps{
        sh 'ls'
      }
    }
    stage('run'){
      steps{
        sh '/bin/bash test.sh'
      }
    }
  }
}
