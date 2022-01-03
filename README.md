# Egenproject1

## PROJECT

In this project I have done the following things.
Created a cloud repository and check in code in
Deployed application in app engine 
Created a cloud build trigger for changes 
Made changes in the cloud 
Created cloud build to trigger automate rollouts and deployments 

## What is CI/CD?
As the name suggests it means the "Continuous integration", "continues delivery" and "Continuous deployment" which come under development framework.
What happens in the framework I used is right from the beginning from left side of my pipeline I have developer sets a developer codes and application and towards the right most side of the pipeline is where the production code is deployed and maintained by the support guys. This whole pipeline is supported by some open-source products and frame works and processes with which the whole integration and deployment happens.

Continuous Integration: It is a code check in and build which we can do several times a day. we are working on production application the needs continue changes then we need this kind of framework.

Continuous Delivery:     Once the code is ready, we will put that code into our repo where it can be further tested (integration testing, user acceptance testing).

Continuous Deployment:   In continues delivery we do everything to make our product ready, but we don't deploy it automatically into the production. So, in continuous deployment we will the developer's changes from the repo to production automatically.

### Commit change -> Trigger build -> Build -> Notify of build outcome -> Run test -> Notify of test outcome -> Deliver build to environment -> Deploy where necessary

![image](https://user-images.githubusercontent.com/28685243/147947176-c96c312d-8f04-4266-bc1b-f69b4435fb0d.png)

## Benefits of CI/CD
1)	The rate of release is quick
2)	Fails early and fails small. As its very important to have multiple deployments where some times we can check if the code will fail or run.
3)	Less cost with automation 
4)	Throughout the pipeline we can see everything (what the developer did and what is happening in production and deployment).

# CI/CD APP ENGINE WITH CLOUD BUILD
CLOUD REPOSITORIES: Collaborate easily on a fully featured, scalable and private git repository.
CLOUD BUILD: Cloud Build is a service that executes your build on Google Cloud Platform’s infrastructure. This can import source code from a variety of repositories or cloud storage space, execute a build to your specifications, and produce artifacts such as Docker containers or java archives.
APP ENGINE: GCP PAAS offering to deploy your application
CONTAIER REGISTRY: GCP offering to store, manage and secure your docker


## Architecture
![image](https://user-images.githubusercontent.com/28685243/147946822-09e452b5-9deb-484f-b0da-40d89583404f.png)
