# Ever DevOps

## Development Resources

https://github.com/ever-co/dev-pulumi - Deploy and Manage our company Development resources on Clouds

We are using Pulumi, Ansible, Jenkins, Cloudflare and many other tools to provision resources required for our development processes:
- AWS EKS (k8s cluster) / ECR registries
- SonarQube runned in the cluster
- Jenkins running in the cluster with build agents on separate EC2 instance

See https://github.com/ever-co/dev-pulumi/wiki for more information

## Gauzy Platform DevOps

- https://github.com/ever-co/gauzy-pulumi - Deploy and Manage Gauzy Platform on Clouds
- https://github.com/ever-co/gauzy/tree/develop/.deploy - some code less related to cloud infra and more focused on Docker containers builds / k8s manifests
- https://github.com/ever-co/gauzy/tree/develop/.circleci - Circle CI/CD for Gauzy Platform
- https://github.com/ever-co/gauzy/tree/develop/.github/workflows - Github Actions for Docker Builds, CodeQL Analysis, Desktop App builds, etc.

## Ever Platform DevOps 

- https://github.com/ever-co/ever-pulumi - Deploy and Manage Ever Platform on Clouds
- https://github.com/ever-co/ever/blob/develop/.circleci/config.yml - Circle CI/CD for Ever Platform
- https://github.com/ever-co/ever/tree/develop/.deploy - some code less related to cloud infra and more focused on Docker containers builds / k8s manifests


