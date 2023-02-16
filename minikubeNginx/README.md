## Usage

-   Start Minikube: minikube start

-   Create the deployment: kubectl create -f nginx-deployment.yaml (Replace nginx-deployment.yaml with the name of the file containing the deployment configuration that I provided in my previous response)

-   Verify that the deployment was created: kubectl get deployments

-   Create the service: kubectl create -f nginx-service.yaml (Replace nginx-service.yaml with the name of the file containing the service configuration that I provided in my previous response)

-   Verify that the service was created: kubectl get services

-   Access the Nginx web server:

-   a. Get the URL for the service: minikube service nginx-service --url

-   b. Open the URL in a web browser or use curl to access the web server from the command line.