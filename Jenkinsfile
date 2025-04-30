pipeline {
  agent any
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  stages {
    stage('Scan') {
      steps {
        script{
          sh 'chmod +x ./mvn'
          withSonarQubeEnv(installationName: 'Sq1'){
          sh './mvn clean org.sonarsource.scanner.maven:sonar-maven-plugin:3.9.0.2155:sonar'
        }
        }
      }
    }
  }
}