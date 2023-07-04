# AzureProjects-Kubernetes-CICD

Please refer to the following repo for the step-by-step process on how to deploy a CI/CD environment. [Project Repo](https://github.com/esolace88/Azure-Projects/tree/main/Kubernetes-CICD)


## For Testing of the Application ## 

## Running the app

You need a Java JDK 7 or later to run the build. You can run the build like this:

    ./gradlew build

You can run the app with:

    ./gradlew npm_start

Once it is running, you can access it in a browser at http://localhost:8080

## Autosclaer Option
https://github.com/kubernetes-sigs/metrics-server

    kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml

