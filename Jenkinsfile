node {
 stage ('SCM Checkout'){
  git 'https://github.com/narendrakoganti7/jenkins_pipelines.git'
  
 }
 stage ('compile-package') {
  tool name: 'maven-3.6.2', type: 'maven'
  
  sh mvn package
 }


}
