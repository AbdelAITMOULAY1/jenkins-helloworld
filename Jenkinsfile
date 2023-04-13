node{
  stage('SCM Checkout'){
    git 'https://github.com/AbdelAITMOULAY1/jenkins-helloworld'
  }
  stage('Compile-Package'){
      def mvnHome = tool name: 'maven3', type: 'maven'
      sh "${mvnHomz}/bin/mvn package"
   }      
}
