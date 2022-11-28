Use Terraform to Create a Kubernetes Deployment with Nginx

1. Create Your Kubernetes Cluster
- Once logged in to your instance, change into the lab-deploy-kubernetes directory.
- Use kind and the kind-config.yaml file to create a cluster named lab-terraform-kubernetes.
- Point kubectl at your cluster to allow interaction.

2. Configure Terraform for Use with the Kubernetes Cluster
- Gather cluster information to input values for your variables file.
- Edit your terraform.tfvars file and add your cluster host and client certificate values.
- Initialize your working directory.

3. Deploy Resources to the Kubernetes Cluster
- Download the added resources configuration file from the repo.
- Review the file.
- Schedule an NGINX deployment with two replicas on your Kubernetes cluster using Terraform.
- Verify the deployment.
