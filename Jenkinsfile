node{
    stage('SCM Checkout'){
        git 'https://github.com/qasimzfr/jenkins-example'
    }
    sage('Compile-Package'){
        sh 'mvn package'
    }
}
