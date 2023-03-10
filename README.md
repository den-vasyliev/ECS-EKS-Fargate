# ECS-EKS-Fargate
Comparison Chart
| Feature                | Amazon ECS                               | Amazon EKS                                                   | AWS Fargate                   |   |
|------------------------|------------------------------------------|--------------------------------------------------------------|-------------------------------|---|
| Type                   | Container Orchestration Service          | Kubernetes Container Orchestration                           | Serverless Container Engine   |   |
| Cluster Management     | Fully managed                            | Fully managed                                                | Fully managed                 |   |
| Deployment             | Blue/Green, Canary, Rolling              | Rolling                                                      | Rolling                       |   |
| Autoscaling            | Manual or Dynamic                        | Horizontal Pod Autoscaler (HPA)                              | Automatic or Manual           |   |
| Load Balancing         | Elastic Load Balancing (ELB)             | Application Load Balancer (ALB), Network Load Balancer (NLB) | Elastic Load Balancing (ELB)  |   |
| Compute Resources      | EC2 Instances                            | EC2 Instances                                                | Serverless                    |   |
| Pricing Model          | Pay for EC2 Instances                    | Pay for EC2 Instances and EKS Control Plane                  | Pay for Compute Resources     |   |
| Networking             | VPC and Security Groups                  | VPC and Security Groups                                      | VPC and Security Groups       |   |
| Container Management   | Task Definitions and Container Instances | Kubernetes Pods                                              | Tasks and Services            |   |
| Customizable           | Customizable task definitions, IAM roles | Customizable worker nodes, Kubernetes YAML                   | Customizable task definitions |   |
| Integration            | Integration with AWS services            | Integration with AWS services                                | Integration with AWS services |   |
| Logging and Monitoring | AWS CloudWatch, AWS X-Ray                | Kubernetes Metrics and Logs                                  | AWS CloudWatch, AWS X-Ray     |   |
