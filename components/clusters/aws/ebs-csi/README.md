# AWS EKS configuration component 2

This component configures:

- Ingress to use AWS Load Balancer Controller
- Storage Class to use AWS EBS CSI driver with `kubernetes.io/aws-ebs` storageClass provisioner
  - Use this provisioner when using the AWS EBS CSI driver as Amazon EKS add-on
testing to see if this works for a branch name that previously existed
