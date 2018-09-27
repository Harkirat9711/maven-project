pipeline{
   agent any
   stages('Build'){
      steps{
       sh 'mvn clean package'
       sh 'docker build . -t tomcatwebapp:${env.BUILD_ID}'
}

}
}
