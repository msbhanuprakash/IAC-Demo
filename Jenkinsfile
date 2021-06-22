Jenkinsfile (Declarative Pipeline)
pipeline  {
    agent { docker  { image 'maven:3.3.3.' } }
    stages {
      Stage {('build')  {
          steps  {
              sh 'mvn --version'
          }
       }
    }
 }
