pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'testing'
          }
        }

        stage('test1') {
          steps {
            echo 'test2'
          }
        }

        stage('test') {
          steps {
            sleep(time: 1, unit: 'SECONDS')
          }
        }

      }
    }

  }
}