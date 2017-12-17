pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        withMaven(
            maven: '3.5.2',
            mavenLocalRepo: '.repository') {
                sh 'mvn -B -DskipTests clean package'
        }
        
      }
    }
  }
}
