pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        dotnetBuild(configuration: 'Release')
      }
    }

  }
}