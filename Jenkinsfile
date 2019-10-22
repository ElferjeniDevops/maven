node
   {
     stage('SCM Checkout') 
          {
              
              git 'https://github.com/ElferjeniDevops/maven'
          }
     stage('Compile-package')
          {
              deh mvnHome = tool name: '', type: 'maven'
             sh  "${mvnHome}/bin/mvn package"
          }
   }  
           
     
