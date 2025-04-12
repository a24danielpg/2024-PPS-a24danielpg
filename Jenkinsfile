/*
pipeline {
   agent any
   stages {
      stage('Build') {
         steps {
            echo 'Tarefas para construir, instalar,...'
         }
      }
      stage('Comprobación inicial') {
         steps {
            sh "ls"
         }
      }
      stage('Deploy') {
         steps {
            echo 'Tarefas para desplegar, construir, ...'
         }
      }
   }
}
*/


pipeline {
    agent {
      docker { image 'python:3' }
    }
    stages {
      stage('Test') {
        steps {
          sh 'python --version'
      }
    }
  }
}
