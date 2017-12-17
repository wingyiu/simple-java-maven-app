pipeline {
  agent any
  tools {
        //工具名称必须在Jenkins 管理Jenkins → 全局工具配置中预配置。
        maven '3.5.2'
    }
  stages {
    
    stage('build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}
