# Terraform_EKS
Terraform templates for Ec2 instance creation on AWS
"eks-cluster.tf" template creates the EKS CLuster and launch the Auto scaling Group with 2 No.of worker nodes
"outputs.tf" template captures the output of the Terraform configuration like VPC ID, EKS Cluster end point etc..
"vpc.tf" template creates the VPC network & Subnets on Us-east-2 region.
"security-groups.tf" templates creates the necessary security group and rules for access.
"kubernetes.tf" declares the Provider details for Terraform
"versions.tf" declares the Terraform template versions.
"deployments.yaml" manisfest to deploy 2 No. of pods running nginx web server
"services.yaml" manifest to allow the LoadBalancer access of Pods from the external world.
