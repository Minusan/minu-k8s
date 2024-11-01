# minu-k8s

This is the way to do it
1. Sugar
2. Spice
3. Everything nice

The following repository containes a simple node application and the terraform files to daploy a simple aks cluster in Azure.
1. Deploy AKS cluster using Azure DevOps

Prerequisite: Azure Subscription, App Registration in Microsoft Entra and an AzureRM connection in Azure devops.

To deploy the cluster We are going to use Terraform install , init, plan and apply tasks from the marketplace

2. To run and test the application locally this can be done using Docker desktop with the Kubernetes extension
kubect apply -f appquickstart.yaml

3. Deploy application using Azure DevOps

To deploy the application we have a appquickstart.yaml k8s manifest file which we can use to deploy the application
we can use an azure cli task to connect to the deployed cluster and deploy the manifest file.