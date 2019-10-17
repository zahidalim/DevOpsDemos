node {
  stage ('SCM Checkout'){
    git 'https://github.com/zahidalim/my-app' 
   }
  stage('Compile-Package'){
    sh 'mvn package'
  }
 }
