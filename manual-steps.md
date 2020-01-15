# Steps currently manual

1. Create NFS Volume in same VPC
2. Create security group which allows SSH from cluster nodes and attach to NFS
3. Allow cluster nodes inbound NFS from EFS security group
