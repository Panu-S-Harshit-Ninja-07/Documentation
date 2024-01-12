# Purpose 

This document will explore some of the popular tools that can help you enable GitOps workflow in your application environment by automating the testing and deployment of IaC codes.


***

## This document includes evaluation of three GitOps tools:
Multiple GitOps tools come with different features and may not cover all GitOps needs. Still, we recommend trying out these  popular GitOps tools:-
* ArgoCD 
* FluxCD
* Jenkins X

***
# ArgoCD 
![image](https://github.com/avengers-p7/Documentation/assets/156056413/667bc1b0-10e2-4148-b57e-ccdc988a83ca)

Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes,responsible for continuously monitoring all running applications and comparing their live state to the desired state specified in the Git repository.

# FluxCD
![image](https://github.com/avengers-p7/Documentation/assets/156056413/a6601987-a3d0-4362-9e72-754900b9eeb2)

Flux CD is a Continuous Delivery tool to help keep Kubernetes clusters in sync with configuration sources such as Git repositories and automate configuration updates when available. Flux is built with the GitOps toolkit and supports multi-tenancy and syncing an arbitrary number of Git repositories.


# Jenkins X
![image](https://github.com/avengers-p7/Documentation/assets/156056413/7864044f-dd4d-4692-b887-15f9d551c41d)

Jenkins X automates and accelerates Continuous Integration and Continuous Delivery for developers on the cloud, so they can focus on building awesome software,The entire Jenkins X experience is based around Git. The installation, extensions and applications you develop are managed via a cluster Git repository which is the desired state of your Kubernetes cluster.

***
# Technical Specifications
| **Topic** | **ArgoCD** | **FluxCD** | **Jenkins X** |
| ------- | ------ | ------ | --------- |
| **Pre-Requisites** | Kubernetes Cluster (v1.23 and later)| Kubernetes Cluster (v1.26 and later) | Kubernetes Cluster |
| **System requirements** | 2 CPU cores and 4GB of RAM | 2 CPU cores and 4GB of RAM  | 2 CPU cores and 4GB of RAM  |
| **Important Ports** | 80,443 | 80,443 | 8080,80,443 |
| **Dependency** | kubectl | kubectl,Git | kubectl,Git |

***
#  Tools Comparison: ArgoCD vs FluxCD vs Jenkins X

| **Feature** | **ArgoCD** | **FluxCD** | **Jenkins X** |
| ------- | ------ | ------ | --------- |
| **Primary Use Case** | Continuous Delivery for Kubernetes | GitOps for Kubernetes | CI/CD for Kubernetes and Cloud Native Apps |
| **Supported Platforms** | Kubernetes | Kubernetes	| Kubernetes, Cloud-Native Platforms |
| **Integration with Git** | Git-based configuration | GitOps workflow | GitOps workflow |
| **CLI Tool** | Yes (Argo CLI) | Yes (fluxctl) | Yes (jx CLI) |
| **User Interface** | Web-based UI | Web-based UI | Web-based UI |
| **Customization** | Highly customizable | Custom controllers for adaptability | Extensible and customizable |
| **Helm Support** | Yes | Yes | Yes |
| **Community Support** | Active | Active | Active |
| **Programming Language** | Go | Go | Java, Groovy, Shell |
| **CI Integration** | Integration with various CI tools | Integration with various CI tools | Integrated CI functionality |

***

# Conclusion

Ultimately, the best tool depends on your specific use case. If you're focused on pure GitOps, both ArgoCD and FluxCD are strong contenders. If you require a more comprehensive CI/CD solution integrated with GitOps principles, Jenkins X might be the preferred choice. It's recommended to evaluate each tool based on your project's needs, infrastructure, and team expertise. Additionally, consider factors such as community support, documentation, and ongoing development activity when making your decision.

***
## Contact Information:
| Name | Email address |
| ---- | ------------- |
| Vishal | vishal.kesarwani.snaatak@mygurukulam.co |

***
## References:
| Source | Description |
| ------ | ----------- |
| https://www.w6d.io/blog/gitops-tools/ | Gitops Tools Features |
| https://loft.sh/blog/gitops-kubernetes-comparing-argo-cd-vs-jenkins-x-vs-flux-vs-spinnaker/ | Gitops Tools Features |
| https://www.devopsschool.com/blog/list-of-gitops-tools/ | Gitops Tools Architecture |
| https://www.tynybay.com/our-thinking/argocd-vs-fluxcd-vs-jenkins-x-which-gitops-implementation-tool-suits-you-the-best#:~:text=Argo%20CD%20supports%20multi%2Dtenancy,with%20a%20set%20of%20cons. | Gitops Tools Installation |