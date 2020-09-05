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
        echo '----Testing has started----'
      }
    }

    stage('DemoDeploy') {
      steps {
        echo '----Deployment has started----'
      }
    }

  }
}