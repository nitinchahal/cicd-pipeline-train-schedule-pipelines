pipeline{
  agent any
  stages{
    stage('Buid') {
      steps{
        echo 'Running Build autoamasdatsion'
        sh' ./gradlew build --no-daemon'
        echo 'Build COmplete'
      }
    }
  }
}
