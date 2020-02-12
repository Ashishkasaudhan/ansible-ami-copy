pipeline {
  agent {
    label 'slave'
  }
  stages {
    stage('packer validate ') {
      steps {
        sh 'packer inspect eks-worker-al2.json'
      }
    }

  }
}