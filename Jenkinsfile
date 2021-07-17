pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
       echo "build step"
       sleep 10 
      }
    }
    stages {
    stage('test'){
      steps {
       echo "test step"
       sleep 10 
      }
    }
      stages {
    stage('deploy'){
      steps {
       echo "deploy step"
       sleep 10 
      }
    }
        stages {
    stage('docker image'){
      steps {
       echo "docker image step"
       sleep 10 
      }
    }
  }
}
