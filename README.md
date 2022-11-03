👋 Hi, I’m @brunobritorj

Here is a list with sample deployments:

- [azdevops/brunobritorj/terraform-azure-k8s/terraform-azure-k8s](https://dev.azure.com/brunobritorj/terraform-azure-k8s/_git/terraform-azure-infra)

  Pipeline on **Azure DevOps** which uses **Terraform** to deploy **Azure** resources (ACR + AKS) and configure Az DevOps service accounts to establish connections to the deployed resources.
  
- [azdevops/brunobritorj/terraform-azure-k8s/appx](https://dev.azure.com/brunobritorj/terraform-azure-k8s/_git/appx)

  Pipeline on **Azure DevOps** with a basic sample app. It is a container based on nginx:alpine image with a single page index.html. CI/CD defines a 3-stage pipeline with build, dev and prd where with canary deployment.
  
  Good to be used with the above repo.
