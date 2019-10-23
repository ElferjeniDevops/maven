node{
             stage('checkout')
                            {
                         echo 'Hello, git'
                         git 'https://github.com/ElferjeniDevops/maven/'
                        }
                
             stage('Example Build') 
                          { 
                          echo 'Hello, Maven'
                          bat 'mvn --version'
                        }
             stage('validate') 
                          { 
                          echo 'phase de validation de code '
                          bat 'mvn validate'
                        }
 }
      
     
