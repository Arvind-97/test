node{
    stage('SCM CHECKOUT'){
      git 'https://github.com/Arvind-97/test'
    }
    stage('Compile-Package'){
     def mvnHome = tool name: 'maven-3.3.9', type: 'maven'
        sh "${Mavenhome}/usr/share/maven package"
    }
 
}
