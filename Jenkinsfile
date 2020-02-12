pipeline {
  agent {
    docker {
      label 'slave'
      image 'ashishkasaudhan/k8s:amazon'
    }

  }
  stages {
    stage('pull code') {
      steps {
        echo 'java -version'
      }
    }

  }
}
