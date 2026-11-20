

\# AWS EKS Kubernetes Mini Project



\## Project Title

Deploy NGINX Application on Amazon EKS using Kubernetes.



\## Project Objective

To create an Amazon EKS cluster, configure worker nodes, deploy an NGINX application, scale Kubernetes pods and expose the application using an AWS Load Balancer.



\## AWS Services Used

\- Amazon VPC

\- Amazon EKS

\- Amazon EC2

\- AWS IAM

\- Elastic Load Balancing



\## Tools Used

\- AWS Management Console

\- AWS CLI

\- kubectl

\- Kubernetes

\- NGINX

\- Git

\- GitHub



\## Project Architecture



VPC

&#x20; |

EKS Cluster

&#x20; |

Managed Node Group

&#x20; |

Worker Nodes

&#x20; |

Kubernetes Deployment

&#x20; |

NGINX Pods

&#x20; |

Load Balancer

&#x20; |

Web Browser



\## Implementation Phases



\### Phase 1 - VPC Creation

Created VPC with two public subnets.



\### Phase 2 - EKS Cluster

Created Amazon EKS cluster.



\### Phase 3 - IAM Configuration

Configured EKS Cluster Role and Node Group Role.



\### Phase 4 - Node Group

Created Managed Node Group with EC2 worker nodes.



\### Phase 5 - Cluster Access

Configured AWS CLI and kubectl.



\### Phase 6 - NGINX Deployment

Deployed NGINX application using Kubernetes.



\### Phase 7 - Scaling

Scaled NGINX deployment to four replicas.



\### Phase 8 - Load Balancer

Exposed NGINX application using LoadBalancer Service.



\## Kubernetes Commands



```bash

kubectl get nodes

kubectl get deployments

kubectl get pods

kubectl get svc

kubectl get all

```



\## Screenshots

Project screenshots are available in the screenshots folder.



\## Learning Outcomes

\- AWS EKS Cluster Management

\- Kubernetes Deployment

\- Pod Management

\- Kubernetes Scaling

\- Load Balancer Configuration



\## Author

Sagar Zinjad



\## Project Status

In Progress



