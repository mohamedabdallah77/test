pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        openshiftExec(pod: 'test', authToken: 'sha256~94VO2lVGFIBoQbKYyuff_xkSmv8GbQ49ECHOzuzNb4U', command: 'oc new-project abdallah', namespace: 'abdallah')
      }
    }

  }
}