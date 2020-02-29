pipeline {
   agent any
   stages {
stage("GIT Checkout"){
steps{
git credentialsId: '14d3bd9c-7505-43f3-97eb-37a435a99336', url: 'https://github.com/md30477/30477self.git'

}
}
stage("Execute Regression Test Suite"){
steps{
  bat 'mvn verify'

}
}
}

}
