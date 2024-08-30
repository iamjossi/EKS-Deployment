# EKS-Deployment
Project Description:

This project sets up an Amazon Elastic Container Service for Kubernetes (EKS) cluster and deploys a sample Nginx application with load balancing, horizontal pod autoscaling, and ingress routing.

Steps Taken

1.Installed required tools: AWS CLI, kubectl, and eksctl.
2.Created an EKS cluster: Named "my-eks-cluster" in the "us-east-1" region with 3 nodes.
3.Deployed a sample application: Nginx deployment with 3 replicas.
4.Exposed the application: Created a LoadBalancer service named "my-service".
5.Set up Horizontal Pod Autoscaler (HPA): Configured to scale between 3 and 10 replicas based on CPU utilization.
6.Configured permissions: Added IAM user account to the "system:masters" group. Only necessary if you can't view resources in the cluster
7.Created an Ingress Resource: Defined a rule for routing traffic to the Nginx service.
8.Deleted resources: Removed the service and EKS cluster at the end.


This project demonstrates a basic setup for deploying and managing a containerized application on an EKS cluster with load balancing, autoscaling, and ingress routing.


Codes for installation of Kubectl and Eksctl and all other configuration codes are included in this repository.
