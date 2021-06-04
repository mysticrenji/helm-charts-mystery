# helm-charts-mystery
Helm Charts mystery solved

## EKS
### AWS EBS
1. Create storage class - Dynamic Provisioning
2. Create Persistence Volume Claim

### AWS EKS LoadBalancer
1. Default load balancer is Class Load Balancer

### AWS EKS NLB
1. Change need to be added in the annotations-
2. Two modes - Instance and IP modes. Instance will route traffic to Nodes - Node service. IP mode will route traffic to pods IP.
3. Supports context based routing and

### AWS EKS ALB 
1. Need to create a service account and map it with IAM role which has access to AWS resources
