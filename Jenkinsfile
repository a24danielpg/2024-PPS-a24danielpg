pipeline {
   agent any
   stages {
      stage('Build') {
         steps {
            echo 'Tarefas para construir, instalar,...'
         }
      }
      stage('Test') {
         steps {
            echo 'Tarefas para realizar test.'
         }
      }
      stage('Deploy') {
         steps {
            echo 'Tarefas para desplegar, construir, ...'
         }
      }
   }
}

/*
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
*/
