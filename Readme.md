# Deploy Hugo app on kubernetes

Note: you can use the help of  [Killercoda playgrounds](https://killercoda.com/playgrounds) for performing the below labs

In this exercise you will learn 
- How to build Docker image from a Dockerfile 
- Run Docker containers based on the image you create 
- Push the image to a remote container image registry.
- And finally to deploy to Kubernetes

In this repo, we have a Hugo-based website along with a Dockerfile, which will be used to build a container image for this application.

## Step 1 - Analyse the dockerfile and build docker image

 - In the repo, we have a  "multi-stage build" docker file.
 - Perform an image build of the website using the docker build command on your windows laptop
 - Run a container using the image and expose it on 8080 and access the website on your laptop using http://localhost:8080
 - Check the size of the image that got created

 ## Step2 - Push the docker image to registry

 - Create a public repo on docker hub or AWS ECR
 - Push this image you created to the above public docker registry
 
 ## Step3 - Deploy to kubernetes

 - Examine the yaml files in the reop and make the required changes based on the docker repository.
 - Deploy the application by using kubectl command.
 - Valdiate the application using the exposed Nodeport service




