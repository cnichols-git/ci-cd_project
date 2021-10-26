# CI | CD Project  
  project for learning how to ...  

  - Build app and change with automation  
  - Run infrastructure in containers
  - 
## To Begin
Make a git repo and start making a list of all the things we will need to make this project going. 
### What to expect
We should expect everything to change and break along the way. 
<pre>
We will become the water.  
     - Bruce Lee
</pre>  
Index:  
[Things we will need](#things-we-will-need)  
[Container Management](#container-management)  
## Ensure you know how to procure, start and use a container  
Make sure you have access to Dockehub to house and get docker images
dockerhub.com 
# Container Management
## Why are we using a container organization tool?  
make a container that runs a website  
<pre>docker container run -d -p 8888:8080 xxx</pre>
Now set up a load balancer in front of that website container  
Make another container but do not specify the IP and only the port of :8080  
<pre>docker container run -d -p 8080 xxx</pre>
What is the **IP** and how or what keeps track of that?  
### ^^Kubernetes is a management plan for your containers that solves the above issue^^  

## Things we will need  
  - Webserver
  - Containers
  - App or website
  - Version control
  - Automation - jenkins??
  - Nodejs
  - Wordpress
  - Do we really want to mess with a db right now  
  - Minikube
  - Dockerhub access & account
  - Docker installed on Deploy System

** I will update the actual list of software and infrastructure as I go **  


### Minikube 
General Notes:  
commands  
- minikube showdashboard - launches browser for Kubernetes cluster that is running
-


