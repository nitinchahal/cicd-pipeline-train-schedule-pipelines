pipeline{
  agent any
  stages{
    stage('Buid') {
      steps{
        echo 'Running Build autoamatsion'
        sh' ./gradlew build --no-daemon'
        echo 'Build COmplete'
      }
    }
  }
}
