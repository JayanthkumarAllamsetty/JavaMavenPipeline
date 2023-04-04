node{
  stage('SCM Checkout'){
    git branch:'main',url: 'https://github.com/JayanthkumarAllamsetty/JavaMavenPipeline.git'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'Maven', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
