# Jenkins_test

### Download Apache Maven example project

- Install maven 
- Run command `mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false` in terminal 
- Build in Jenkins  
- Install Jenkins controller and agent 

### Run Jenkins on Docker 
- Download Docker and build the Jenkins docker image 
`docker build -t myjenkins-blueocean:2.332.3-1 .` 
