node {
 
  def mvnHome = tool 'gradle61' 


stage('Checkout') {


 git 'https://github.com/tfang54321/firstAngular1029.git'
mvnHome = tool 'gradle61' 

}


stage('buildimage') {


//sh  "'${mvnHome}/bin/gradle'   docker"
 
// sh " docker run -p 8091:8080 ca.gc.dfo/gs-spring-boot-docker-psffs1126"
  
  sh "docker image build -t firstangulardockerimage1127 ."


}
}
