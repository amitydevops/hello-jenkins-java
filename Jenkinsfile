pipeline {
   agent any

   stages {
      stage('Checkout') {
         steps {
            git 'https://github.com/amitydevops/hello-jenkins-java.git'
         }
      }
      stage('Build'){
        steps {
            sh 'javac HelloJenkins.java'
        }
      }
   }
}
