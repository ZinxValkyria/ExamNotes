# Kubernetes Revision

## Kubernetes Basics

### Container Orchestration
- **Definition:** Automated deployment, scaling, and management of containerized applications.
- **Key Components:** Nodes, Pods, Services, Deployments.

### Kubernetes Architecture
- **Master Node:** Controls and manages the cluster.
- **Worker Node:** Hosts containers and runs applications.

### Key Components

#### Pods
- **Definition:** Smallest deployable units in Kubernetes.
- **Purpose:** Encapsulates one or more containers.

#### Services
- **Definition:** Network abstraction to expose applications.
- **Types:** ClusterIP, NodePort, LoadBalancer, Ingress.

#### Deployments
- **Definition:** Declarative updates to applications.
- **Purpose:** Rolling updates and rollbacks.

#### ConfigMaps and Secrets
- **ConfigMaps:** Store configuration data.
- **Secrets:** Store sensitive information.

### Kubernetes CLI (kubectl)
- **Command-Line Tool:** Interact with Kubernetes clusters.
- **Usage:** Deployments, scaling, inspection.

## Kubernetes Workloads

### Deployments
- **Imperative vs. Declarative:** Describing desired state vs. issuing commands.
- **Rolling Updates:** Gradual replacement of instances with new versions.

### StatefulSets
- **Definition:** Manages stateful applications.
- **Use Cases:** Databases, distributed systems.

### DaemonSets
- **Definition:** Ensures a copy of a Pod runs on all nodes.
- **Use Cases:** Monitoring agents, log collectors.

### Jobs and CronJobs
- **Jobs:** Runs until completion.
- **CronJobs:** Scheduled jobs.

## Kubernetes Networking

### Cluster Networking
- **Pod-to-Pod Communication:** Pods can communicate without NAT.
- **Service Discovery:** Automatic DNS for service discovery.

### Ingress Controllers
- **Definition:** Manages external access to services.
- **Configuration:** Define rules for routing traffic.

## Kubernetes Security

### RBAC (Role-Based Access Control)
- **Definition:** Regulate access to the Kubernetes API.
- **Principles:** Users, Roles, RoleBindings.

### Pod Security Policies
- **Definition:** Control over a pod's security context.
- **Settings:** Define what a pod can and cannot do.

### Network Policies
- **Definition:** Specify how groups of pods can communicate.
- **Control:** Ingress and egress traffic control.

## Kubernetes Ecosystem

### Helm
- **Package Manager:** Simplifies deploying applications on Kubernetes.
- **Charts:** Packages of pre-configured Kubernetes resources.

### Operators
- **Definition:** Framework to manage complex, stateful applications.
- **Custom Resource Definitions (CRDs):** Extend Kubernetes API.

### Kubernetes Monitoring
- **Prometheus:** Open-source monitoring and alerting toolkit.
- **Grafana:** Visualization and monitoring dashboard.

## Study Resources

### Kubernetes Documentation
- [Kubernetes Documentation](https://kubernetes.io/docs/)

### Kubectl Cheat Sheet
- [Kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

### Interactive Scenarios
- [Kubernetes Interactive Scenarios](https://kubernetes.io/docs/tutorials/kubernetes-basics/)

## Exam Tips

- **Understand Core Concepts:** Nodes, Pods, Services, Deployments.
- **Practice with kubectl:** Familiarize yourself with common commands.
- **Hands-On Experience:** Set up and manage a simple Kubernetes cluster.

Best of luck with your Kubernetes learning journey and any certification pursuits!
