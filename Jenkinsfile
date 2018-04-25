pipeline {
  agent any
  stages {
    stage('prepration') {
      steps {
        echo 'Code  and  fetched'
      }
    }
    stage('build') {
      steps {
        bat 'mvn clean package'
      }
    }
    stage('Test') {
      steps {
        echo 'testing'
      }
    }
    stage('Deploye') {
      steps {
        echo 'Deploye stage'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_161'
    MAVEN_HOME = 'C:\\Program Files\\apache-maven-3.5.3'
  }
}