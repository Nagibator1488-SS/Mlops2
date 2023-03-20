pipeline {
  agent any
  stages {
    stage('version1') {
      steps {
        sh 'apt install python3-pip'
      }
    }
    stage('version2') {
      steps {
        sh 'pip install wget'
      }
    }
    stage('hello3') {
      steps {
        sh 'pip install scikit-learn'
      }
    }
    stage('version4') {
      steps {
        sh 'pip install pandas'
      }
    }
    stage('version5') {
      steps {
        sh 'pip install requests'
      }
    }
    stage('version6') {
      steps {
        sh 'python3 Load.py'
      }
    }
    stage('version7') {
      steps {
        sh 'python3 Standartization.py'
      }
    }
    stage('version8') {
      steps {
        sh 'python3 Training.py'
      }
    }
    stage('version') {
      steps {
        sh 'python3 Result.py'
      }
    }
  }
}