# Learn Terraform - Provision an EKS Cluster

Terraform configuration files to provision an EKS cluster on AWS.

aws eks --region $(terraform output -raw region) update-kubeconfig --name $(terraform output -raw cluster_name)
# eks_using_terraform
