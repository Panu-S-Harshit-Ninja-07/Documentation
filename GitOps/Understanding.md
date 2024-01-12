
# Introduction
GitOps is code-based infrastructure and operational procedures that rely on Git as a source control system. It’s an evolution of Infrastructure as Code (IaC) and a DevOps best practices that leverages Git as the single source of truth, and control mechanism for creating, updating, and deleting system architecture.

***
# Why GitOps

GitOps is a modern approach to managing and deploying infrastructure and applications that leverages Git as the central source of truth. Here are key points:

* **Version Control:** GitOps uses Git for version control, enabling teams to track changes, collaborate effectively, and maintain an audit trail of modifications.

* **Declarative Configuration:** GitOps relies on declarative configurations, specifying the desired state rather than procedural steps. This enhances readability and reduces configuration drift.

* **Infrastructure as Code (IaC):** GitOps promotes Infrastructure as Code (IaC) principles, allowing for automated provisioning and management of infrastructure.

* **Automation:** Automation is a core aspect of GitOps, facilitating continuous delivery and deployment, reducing human errors, and ensuring consistent and repeatable processes.

* **Auditing and Compliance:** GitOps provides a clear audit trail of changes, aiding in compliance efforts and allowing for accountability in the event of issues.

* **Consistency Across Environments:** GitOps ensures consistency in configurations and infrastructure across different environments, from development to production.

* **Rollback and Rollforward:** GitOps simplifies the process of rolling back to previous states or applying changes in a controlled manner by leveraging Git's versioning capabilities.

* **Collaboration and Visibility:** GitOps encourages collaboration among team members through Git's collaboration features, promoting better communication and visibility into system changes.

* **Multi-Cloud and Hybrid Cloud:** GitOps is adaptable to multi-cloud and hybrid cloud environments, making it suitable for organizations with diverse infrastructure needs.
***
# GitOps Principles 
* **Declarative:** System configurations are expressed declaratively, leveraging Git as the authoritative source of truth. This approach simplifies deployment, rollback, and disaster recovery by focusing on defining the desired state rather than explicit instructions.

* **Versioned and Immutable:** The system's canonical state is stored and versioned in Git, offering a reliable repository for configurations. This enables straightforward rollbacks and creates an immutable version store, essential for maintaining a secure audit trail.

* **Pulled Automatically:** Approved changes are automatically applied to the system, promoting an automated deployment workflow. GitOps allows for separation between the defined state and execution, minimizing manual interventions and emphasizing automated tests and checks.

* **Continuously Reconciled:** Software agents continuously monitor and alert on disparities between the declared and actual system states. These agents contribute to self-healing capabilities, addressing discrepancies and errors in real-time.
***
# GitOps Tools 
* **ArgoCD** - Declarative continuous deployment for Kubernetes
* **Atlantis** - Terraform pull request automation
* **Autoapply** - Automatically apply changes from a Git repository to a Kubernetes cluster
* **Carvel** — Tool suite for building, packaging, and managing software on Kubernetes in a GitOps way
* **CloudBees Rollout** - Feature Flag as-a-Service that leverages GitOps & Config-as-Code (commercial product from CloudBees)
* **Flux** - Open and extensible continuous delivery solution for Kubernetes. Powered by GitOps Toolkit
* **Helm Operator**- Automates Helm Chart releases in a GitOps manner
* **Flagger** - Progressive delivery Kubernetes operator (Canary, A/B testing and Blue/Green deployments automation)
* **Ignite**- A Virtual Machine manager with a container UX and built-in GitOps
* **Faros** - CRD based GitOps controller
* **Jenkins X** - a CI/CD platform for Kubernetes that provides pipeline automation, built-in GitOps and preview environments
* **KubeStack** - GitOps framework using Terraform for Cloud Kubernetes distros (AKS, GKE, and EKS) with CI/CD examples for common tools
* **Sceptre** - Sceptre is a tool to drive AWS CloudFormation as part of a CI/CD pipeline by using Hooks
* **Weave GitOps OSS** - Weave GitOps is a simple open source developer platform for people who want cloud native applications, without needing Kubernetes expertise.
* **Weave GitOps Enterprise**- Weave GitOps Enterprise is a continuous operations product that makes it easy to deploy and manage Kubernetes clusters and applications at scale in any environment. (commercial product from Weaveworks)
* **Werf** - GitOps tool with advanced features to build images and deploy them to Kubernetes (integrates with any existing CI system)
* **PipeCD** - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications
* **Grant.rs**- Manage Redshift/Postgres privileges in GitOps style
* **Gimlet** - The Flux-based Internal Developer Platform
***
# GitOps Workflows and Procedures
*** 
# Benefits of GitOps
The underlying Git protocol isn't resource-intensive and is open source. It offers the following additional benefits:

* Increased productivity through the enablement of CD and deployment.
* Reliability and security through declarative states, versioned storage, continuous state reconciliation, revert and rollback, and fork features.
* Standardized workflows centered around Git.
* A single set of tools.
* A reduced number of potential variables in infrastructure management.
* Visibility and a clear change history.
* Smaller potential attack surfaces.
*** 
# Drawbacks of GitOps
Some disadvantages of GitOps, however, include these drawbacks:

* Teams must look out for broken YAML manifests, in which syntax or object references could be broken.
* By handling development through a pull approach, teams are limited to using only tools that execute pulls.
* There's the potential for application programming interface throttling, as GitOps consistently polls Git repositories.
* Large teams that frequently make updates might push a change at the same time, writing to the same files simultaneously.
* At scale, matching an environment's desired state to Git is difficult without more tools.
* GitOps doesn't offer a way to manage authentication or other sensitive data without additional tooling.

*** 
# GitOps Best Practices
***
# Frequently Asked Questions 
***
***
## Contact Information:
| Name | Email address |
| ---- | ------------- |
| Aakash | aakash.tripathi.snaatak@mygurukulam.co |

***
## References:
| Source | Description |
| ------ | ----------- |
| https://www.techtarget.com/searchitoperations/definition/GitOps | Gitops Features |
| https://www.weave.works/technologies/gitops/ | Gitops Principles |
