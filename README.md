# What is This

A simple repo for creating shared storage for a Openshift cluster on AWS


Right now some manual steps are required, but these can easily be automated.
Also, files named `nn-sssss-template.yaml` needs to manually be updated before applying.

However, it's a baseline ripe for further automation/standardization.

# Steps currently manual

1. Create NFS Volume in same VPC
2. Create security group which allows SSH from cluster nodes and attach to NFS
3. Allow cluster nodes inbound NFS from EFS security group
