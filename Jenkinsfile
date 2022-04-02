pipeline{
  agent { docker { image 'python:3.10.1-alpine' } }
  stages{
  stage('stage1') {
    steps {
        sh 'python a.py'
    }
}
stage('stage2'){
  steps{
    sh 'echo "completed"'
  }
}
  }
}
