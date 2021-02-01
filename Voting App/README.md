# Solution - Voting Application

# Table of Contents
- [Namespace Creation](#namespace-creation)
- [Deployment files](#manifest-files)

## Namespace Creation
`kubectl create namespace vote`

## Manifest Files
- [Vote Deployment](vote-deployment.yaml)
- [Vote Service](vote-service.yaml)
- [Redis Deployment](redis-deployment.yaml)
- [Redis Service](redis-service.yaml)
- [Worker](worker.yaml)
- [DB Deployment](db-deployment.yaml)
- [DB Service](db-service.yaml)
- [Result Deployment](result-deployment.yaml)
- [Result Service](result-service.yaml)

## Creating Kubernetes object
`kubectl apply -f <filename>.yaml`