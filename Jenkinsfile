node{
    stage('SCM Checkout'){
	git 'https://github.com/qasimzfr/jenkins-example'
    }
    stage('Compile-Package'){
          // Get maven home path
	  def mvnHome = tool name: 'maven-3', type: 'maven'
	  sh "${mvnHome}/bin/mvn package"
    }
}
