pipeline{
  agent any
  stages{
    stage('Buid') {
      steps{
        echo 'Running Build automation'
        sh' ./gradlew build --no-daemon'
        echo 'Build COmplete'
      }
    }
  }
}
