node{
stage('SCM Checkout'){
 
git 'https://github.com/Nikheel1704/ICIN_BANK_USER_LOGIN'
}
stage('Compile-Package'){
  def mvnHome= tool name: 'maven-3', type: 'maven'
  sh "${mvnHome}/bin/mvn package" 
}
}
