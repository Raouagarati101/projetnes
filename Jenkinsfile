node{
   stage('SCM Checkout'){
      git 'https://github.com/nesrinehm1996/projet-test'
   }
   stage('Compile-Package'){
      //get maven home path 
      def mvnHome = tool name: 'maven3.3.9', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }

}
