node{
  stage('SCM Checkout'){
    git 'https://github.com/SolomonBekele/simpledevops'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
    
