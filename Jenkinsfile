pipeline {
    agent any
    stages {
      stage('git checkout') {
        steps{
          git branch: 'main', credentialsId: '0e508f4e-9906-4800-ba5c-90d1dcb67b38', url: 'https://github.com/venkyy8/monday-practice.git'
        }
      }
    }
}
