# Hi, I'm Raz

Second-year IT systems integration apprentice (Fachinformatiker Systemintegration) in Bavaria, Germany.
By day I do IT support and build infrastructure for companies and their customers: Windows, Active Directory, Exchange, backup and network setups.
By night I build and document cloud and DevOps projects, so I understand the tools instead of just using them.

I speak Romanian, German, English and Spanish.

## What I'm working on
- Building an AWS portfolio with Terraform and GitHub Actions, one focused project per repo
- Studying AWS Technical Essentials and preparing for the AWS Certified Cloud Practitioner exam (CLF-C02)
- Running a self-hosted homelab on Proxmox with Kubernetes and GitOps
- Exploring cloud technologies and DevOps practices in depth

## Tools and technologies
| Area | What I use |
|---|---|
| Cloud (AWS) | S3, CloudFront, Lambda, API Gateway, DynamoDB, VPC, EC2, ECS Fargate, ECR, EKS, SQS, SNS, Step Functions, Secrets Manager, CloudWatch, IAM |
| Infrastructure as Code | Terraform (modules, remote state in S3, workspaces for dev and prod) |
| CI/CD | GitHub Actions: plan on every push, manual apply behind an approval gate, OIDC instead of stored keys (newest project) |
| Containers and orchestration | Docker, Kubernetes (k3s, EKS), Helm basics, ArgoCD |
| Systems and networking | Linux, Proxmox, Ansible, Tailscale, Windows Server, Active Directory, Exchange, IPv6, Cisco Packet Tracer |
| Scripting | Python, Bash, PowerShell |

## AWS portfolio projects
Each repo has a short README and a long PROJECT_GUIDE.md that explains every step, every bug and how I fixed it.

| Project | What it shows |
|---|---|
| [terraform-cicd-project](https://github.com/Ralso11/terraform-cicd-project) | Static site on S3 and CloudFront, deployed by Terraform through GitHub Actions with an approval gate |
| [lambda-api-project](https://github.com/Ralso11/lambda-api-project) | Serverless API on Lambda and API Gateway, plus a CloudWatch dashboard and an alarm I triggered on purpose |
| [vpc-networking-project](https://github.com/Ralso11/vpc-networking-project) | VPC with public and private subnets, security groups and EC2, with a one-click destroy workflow |
| [ecs-docker-project](https://github.com/Ralso11/ecs-docker-project) | Dockerized Flask app on ECR and ECS Fargate, built and deployed by the pipeline |
| [terraform-modules](https://github.com/Ralso11/terraform-modules) | Reusable VPC and IAM-role modules with examples that are really deployed in CI |
| [url-shortener-project](https://github.com/Ralso11/url-shortener-project) | Lambda, API Gateway and DynamoDB, with short-code generation and redirects |
| [eks-kubernetes-project](https://github.com/Ralso11/eks-kubernetes-project) | EKS on Fargate with a test pod, built and destroyed in one session because of the hourly cost |
| [secrets-manager-project](https://github.com/Ralso11/secrets-manager-project) | A Lambda reads a secret at runtime and never exposes it |
| [multi-env-project](https://github.com/Ralso11/multi-env-project) | One Terraform codebase for dev and prod, with separate approval rules per environment |
| [sqs-event-driven-project](https://github.com/Ralso11/sqs-event-driven-project) | Asynchronous design: a producer Lambda, an SQS queue and a consumer Lambda with least-privilege roles |
| [step-functions-order-processing-project](https://github.com/Ralso11/step-functions-order-processing-project) | Order workflow with retries and error handling, deployed with GitHub OIDC |

## Homelab
[homelab](https://github.com/Ralso11/homelab): Proxmox VE with Docker, k3s, Ansible, Terraform, ArgoCD and Tailscale, plus monitoring and automated alerts.

## How I work
- Docs first: every step, every decision and every mistake is written down.
- Safe by default: pipelines plan on every push, apply only on request, and costly resources have a destroy workflow.
- Least privilege: separate IAM identities per project, scoped permissions, no secrets in code.
- Cost aware: budgets, short-lived resources, and notes on what each project costs.

## Contact
Always happy to connect with people working in cloud, IT infrastructure, networking and technical sales. You can reach me through the links on my GitHub profile.
