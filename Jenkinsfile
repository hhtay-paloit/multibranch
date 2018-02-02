pipeline {
  agent any

  stages {

    stage('dev') {
      when {
        branch 'dev'
      }
      steps {
        echo 'run dev cicd'
      }
    }

    stage('test') {
      when {
        branch 'test'
      }
      steps {
        echo 'run test cicd'
      }
    }
  }
}
