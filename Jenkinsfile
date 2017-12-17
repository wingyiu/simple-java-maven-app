pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'sh \'mvn -B -DskipTests clean package\''
      }
    }
  }
}