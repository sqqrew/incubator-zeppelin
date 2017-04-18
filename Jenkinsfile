pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "11": {
            sh 'echo 11'
            
          },
          "12": {
            sh 'echo 12'
            
          }
        )
      }
    }
    stage('21') {
      steps {
        sh 'echo 21'
      }
    }
    stage('31') {
      steps {
        parallel(
          "31": {
            sh '31'
            
          },
          "32": {
            echo '32'
            
          }
        )
      }
    }
  }
}