pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        withMaven(globalMavenSettingsFilePath: 'D:\\Jenkins - Alumno\\maven\\conf\\settings.xml', mavenSettingsFilePath: 'D:\\Jenkins - Alumno\\maven\\conf\\settings.xml', maven: 'Maven', jdk: 'java') {
          bat 'mvn clean install -DskipTests'
        }

      }
    }
  }
}