GKE- infrastracture
deploy GkE cluster on GCP cloud in private subnet and allow cluster to access the internet 
create Dockerfile with jenkins,docker CLI and kubectl 
build docker file  using 
   docker build -t jenkins-amira . 
push this image into docker hub   using the following command:
     docker tag jenkins-amira  amirayousef/jenkins-amira
     docker push amirayousef/jenkins
create namespace jenkins 
create service type LoadBalancer to Expose pod in port 8080  
create deployment  nameing "deployment-jenkins" with replica 1
