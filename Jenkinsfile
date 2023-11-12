node{
  stage('SCM Checkout'){
    git 'https://github.com/SolomonBekele/simpledevops'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'MAVEN', type: 'maven'
    sh '${mvnHome}/bin/mvn package'
  }
}
    
