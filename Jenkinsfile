pipeline {
  agent any
  stages {
    stage('Build Base Image') {
      steps {
        sh 'docker build -t quay.io/qiime2/core:$(QIIME2_RELEASE) -t quay.io/qiime2/core:latest --build-arg QIIME2_RELEASE=$(QIIME2_RELEASE) docker'
      }
    }

  }
}