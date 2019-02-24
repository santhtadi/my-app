node{
 stage('SCM Checkout'){
  git 'https://github.com/santhtadi/my-app' 
 }
 stage('Compile-Package'){
  def mvnhome= tool name: 'maven', type: 'maven'
  sh 'pwd'
  sh "${mvnhome}/bin/mvn package"
 }
}
