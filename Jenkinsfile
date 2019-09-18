node {
 stage ('SCM Checkout'){
  git 'https://github.com/narendrakoganti7/jenkins_pipelines.git'
  
 }
 stage ('compile-package') {
  def mvnHome = tool name: 'maven-3.6.2', type: 'maven'
  
  sh "${mvnHome}/mvn package"
 }


}
