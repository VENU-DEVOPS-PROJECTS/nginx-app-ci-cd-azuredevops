# nginx-app-ci-cd-azuredevops

Step 1 :
Writing an Dockerfile which fetches nginx image from dockerhub and building an image from it by chnaging index.html with your customized template .
see Dockerfile for more info .

Step 2 :
Create an azure container registry and add it to the service connections in azure pipelines.

step 3 :
Provision an AZURE CONTAINER INSTANCE which uses the images from the ACR .Run the build pipeline to build image of new version.

step4 :
Access the IP of that ACI u you can access the new built image version from the browser .
