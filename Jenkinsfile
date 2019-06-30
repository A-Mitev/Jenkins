node{
  stage('SCM Checkout'){
  git 'https://github.com/A-Mitev/Jenkins.git'
  }
  stage('Compile-Package'){
   def mvnHome = tool name: 'TestMaven', type: 'maven' 
    sh = "${mvnHome}/bin/mvn package" 
  }
}
