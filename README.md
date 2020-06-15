Use this Quick Start to automatically set up a new Amazon EKS environment. The deployment includes the following:

A highly available architecture that spans three Availability Zones.*
A virtual private cloud (VPC) configured with public and private subnets according to AWS best practices, to provide you with your own virtual network on AWS.*
In the public subnets, managed NAT gateways to allow outbound internet access for resources in the private subnets.*
In one public subnet, a Linux bastion host in an Auto Scaling group to allow inbound Secure Shell (SSH) access to Amazon Elastic Compute Cloud (Amazon EC2) instances in private subnets. The bastion host is also configured with the Kubernetes kubectl command line interface for managing the Kubernetes cluster.
An Amazon EKS cluster, which provides the Kubernetes control plane.
In the private subnets, a group of Kubernetes nodes.

*  The template that deploys the Quick Start into an existing VPC skips the tasks marked by asterisks and prompts you for your existing VPC configuration.

 architecture diagram
 
 <a> https://d1.awsstatic.com/partner-network/QuickStart/datasheets/amazon-eks-on-aws-architecture-diagram.7fdf06380021e6dc7c622d298d99e3c1154163bc.png </a>
