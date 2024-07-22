node {
  stage('SCM Checkout') {
    git 'https://github.com/javahometech/my-app'
  }
  stage('Compile-Package') {
    def mvnHome = tool name: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
