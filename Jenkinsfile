pipeline {
 agent {
  node {
   label 'testing'
  }
 }

 stages {
  stage('Build') {
   steps {
    sh 'python3 helloWorld.py'
   }
  }
  stage('Test') {
   steps {
    echo 'Testing..'
   }
  }
  stage('Deploy') {
   steps {
    echo 'Deploying....'
   }
  }
 }
}
