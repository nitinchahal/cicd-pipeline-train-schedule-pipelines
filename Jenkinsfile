pipeline{
  agent any
  stages{
    stage('Buid') {
      steps{
        echo 'Running Build Updated1'
        sh' ./gradlew build --no-daemon'
        echo 'Build COmplete'
      }
    }
  }
}
