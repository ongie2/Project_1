Deploying an ECS Cluster with a Docker image Using Terraform

# Scenario

You must deploy a Docker container with a centos image for the team.

Get a centos image from the Docker registry.
With Terraform, create an ECS cluster using the Docker image.

# Definitions

Modules: A module is a collection of resources that are utilized together. To define your infrastructure in terms of its design rather than specifically in terms of real items, you can utilize modules to build simple abstractions.

A controlled cluster of Amazon Elastic Compute Cloud (Amazon EC2) instances can be used to execute applications using Amazon Elastic Container Service (ECS), a highly scalable, high-performance container management solution that supports Docker containers.

To build an ECS cluster in Terraform for this project, we'll use a docker image called Centos.

# Project structure

Providers.tf
main1.tf
VPC.tf
variables.tf
