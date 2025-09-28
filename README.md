# Cow wisdom web server

## Message for viewer

if you are reviewing this branch :``` main  ``` it's for the bare Metal vm deployment and the AKS-Cluster branch is for Azure ASK service branch deployment currently the url is being pointed to the AKS service to see the deployment 

## Warning 

if you click on the URL and you find the server not found or Invalid address Probably i have exausted the $10 remaining credit on Azure on AKS service 


## how the website look Before the AKS service stop 


<img width="493" height="341" alt="image" src="https://github.com/user-attachments/assets/095c5b48-ebbd-446e-a342-65312b5eed51" />


## Prerequisites

```
sudo apt install fortune-mod cowsay -y
```

## How to use?

1. Run `./wisecow.sh`
2. Point the browser to server port (default 4499)

## What to expect?
![wisecow](https://github.com/nyrahul/wisecow/assets/9133227/8d6bfde3-4a5a-480e-8d55-3fef60300d98)

# Problem Statement
Deploy the wisecow application as a k8s app

## Requirement
1. Create Dockerfile for the image and corresponding k8s manifest to deploy in k8s env. The wisecow service should be exposed as k8s service.
2. Github action for creating new image when changes are made to this repo
3. [Challenge goal]: Enable secure TLS communication for the wisecow app.

## Expected Artifacts
1. Github repo containing the app with corresponding dockerfile, k8s manifest, any other artifacts needed.
2. Github repo with corresponding github action.
3. Github repo should be kept private and the access should be enabled for following github IDs: nyrahul
