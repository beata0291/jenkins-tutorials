pipeline {
  agent any
  stages {
    stage('one') {
      enviroment {
        abc = credentials("CRED")


      }

      steps {
        echo "HELLO ${abc_USR}"
        echo "HELLO ${abc_PSW}"
      }
    }

  }
}