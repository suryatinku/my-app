
node {
   
   stage('SCM Checkout'){
    git 'https://github.com/javahometech/my-app'
   
   }
 
   stage('Compile-Package'){
	   // Build using maven
	   
	   sh "mvn package"
   }}
