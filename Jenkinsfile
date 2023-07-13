pipeline{
  agent any
  stages{
    stage("make a directory"){
      steps{
        sh "mkdir ~/jenkins-tutorial-test || true"
      }
    }
    stage("create a file"){
      steps{
        sh "touch ~/jenkins-tutorial-test/file1 || true"
      }
    }
    stage("prod stage"){
      steps{
        sh "touch ~/jenkins-tutorial-test/prodfile"
      }
    }
    stage("test stage"){
      steps{
        sh "touch ~/jenkins-tutorial-test/testfile"
      }
    }  
    stage("demo stage"){
      steps{
        sh "touch ~/jenkins-tutorial-test/demofile"
      }
    }
  }
}
