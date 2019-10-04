# cf-k8s-eksctl-stack

## This project create a EKS Cluster and Jenkins for test the Cluster

### You need create a Amazon account and generate credentials with full access

#### 1 - Execute the template "network.yml" first 
#### 2 - Keep the "EnvironmentName", you need use to execute the "eks-server.yml"
#### 3 - Execute eks-server.yml with the same "EnvironmentName"  and the credentials that you created
#### 4 - Wait the instance finish completly, you can check in CloudFormation (the instance will execute other two templates Cloudformation for create a Cluster)

#### Enjoy you cluster, you can check the example application with the LB endpoint