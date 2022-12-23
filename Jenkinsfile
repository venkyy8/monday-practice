pipeline {
    agent any
    environment { 
    PATH = "D:\Tools\apache-maven-3.8.5\bin:$PATH"
}
    stages {
      stage('git checkout') {
        steps{
          git branch: 'main', credentialsId: '0e508f4e-9906-4800-ba5c-90d1dcb67b38', url: 'https://github.com/venkyy8/monday-practice.git'
        }
      }
      stage('test cases') {
        steps{
          sh 'build 'test''
        }
      }
    }
}
