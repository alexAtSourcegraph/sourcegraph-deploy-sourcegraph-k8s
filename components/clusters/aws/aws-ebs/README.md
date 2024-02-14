# AWS EKS configuration component 1

This component configures:

- Ingress to use AWS Load Balancer Controller
- Storage Class to use AWS EBS CSI driver with `ebs.csi.aws.com` storageClass provisioner
  - Use this provisioner when using the self-managed Amazon EBS Container Storage Interface driver
testing to see if this works for a branch name that previously existed
