pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        sh '''git clone https://github.com/Vaibhavi1707/jenkins_maven_pipeline
'''
      }
    }

    stage('Maven test') {
      steps {
        sh '''mvn test
'''
      }
    }

    stage('Maven build') {
      steps {
        sh '''mvn package

'''
      }
    }

    stage('Maven deploy') {
      steps {
        sh '''echo "Deployed on server"
'''
      }
    }

  }
}