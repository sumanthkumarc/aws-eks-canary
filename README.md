# aws-eks-canary
Simple barebones canary implementation on AWS EKS using ALB 


# Requirements
Assumes AWS load balancer controller (https://kubernetes-sigs.github.io/aws-load-balancer-controller) is installed on cluster and able to reconcile Ingress resources with alb IngressClass.
