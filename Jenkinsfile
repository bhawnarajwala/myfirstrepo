pipeline{
  agent { docker { image 'python:3.10.1-alpine' } }
  stages{
  stage('stage1') {
    steps {
        sh 'python code/a.py'
    }
}
stage('stage2'){
  steps{
    sh 'aws s3 cp code/a.py s3://bhawna6451/'
  }
}
  }
}
