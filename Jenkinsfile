pipeline {
  agent any
  stages {
    stage('DemoBuild') {
      agent any
      steps {
        echo '----Building started-----'
      }
    }

    stage('DemoTest') {
      agent any
      steps {
        echo '---Testing has started---'
        sh '''sleep 5
echo success'''
      }
    }

    stage('DemoDeploy') {
      agent any
      steps {
        echo '----Deployment has started----'
        echo '---Deployment has started---'
      }
    }

  }
}