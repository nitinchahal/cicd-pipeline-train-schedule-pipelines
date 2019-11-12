pipeline{
  agent any
  stages{
    stage('Buid') {
      steps{
        echo 'Running Build automatsion'
        sh' ./gradlew build --no-daemon'
        echo 'Build COmplete'
      }
    }
  }
}
