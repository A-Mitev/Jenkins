node{
  stage('SCM Checkout'){
  git 'https://github.com/A-Mitev/Jenkins.git'
  }
  stage('Compile-Package'){
   def mvnHome = tool name: 'maven-3', type : 'maven' 
    sh = "$(mvnHOme)/bin/mvn package" 
  }
}
