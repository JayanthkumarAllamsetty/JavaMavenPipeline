node{
  stage('SCM Checkout'){
    git 'https://github.com/JayanthkumarAllamsetty/JavaMavenPipeline.git'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'Maven', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
