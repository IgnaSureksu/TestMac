pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "Dormir": {
            sleep 34
            
          },
          "Mensaje": {
            echo 'Mensaje impreso'
            
          }
        )
      }
    }
  }
}