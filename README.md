# Pulumi implementation for EKS Cluster creation

Pulumi implementation for EKS Cluster creation

### update aws credentials to access your AWS account 

``` no-highlight
Update credentials file with your AWS Access key Id and Key 
aws_access_key_id=<your aws accerss key id> 
aws_secret_access_key=<your aws accerss key>
```
## Building docker images
``` bash
docker build . -t pulumi-eks-cluster:v1.0
```
## Running docker images
``` bash
docker run  -it pulumi-eks-cluster:v1.0
```

## output logs 
``` no-highlight
 
 
  ```  
 ## EKS Cluster is created and ready to use using arn as above output   
