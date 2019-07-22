class: center, middle, blue
# Cluster Management on Azure

---
### whoami

.left-small[
    ![image](https://pbs.twimg.com/profile_images/994762110792953856/EheEvqBY_400x400.jpg)
]

.right-large[
- Kyohei Mizumoto(@kyohmizu)

- C# Software Engineer

- Interests
    - Docker/Kubernetes
    - Go
    - Security
]

---
### Motivation

- I've been studying kubernetes for half a year

- But I don't use kubernetes for work...

- So, I tried to create cluster by myself

---
class: header-margin
### Why AKS?

<center><img src="azure-subscription-top.png" width=100%></center>
<center><img src="azure-subscription.png" width=100%></center>

---
### Configuration

.zoom1[
- Kubernetes Cluster(AKS)

  - Mattermost

  - Prometheus

  - Grafana

  - Cert Manager
  
  - Fluent Bit

- Azure Load Balancer

- Azure Database for PostgreSQL server

- Azure Key Vault

- Azure Log Analytics
]

---
### Features

.zoom1[
- Monitoring

  - Prometheus + Grafana

- Logging

  - Fluent Bit + Azure Log Analytics

- TLS support

  - Cert Manager

- Secret management

  - Azure Key Vault
]

---
### Problems

.zoom1[
- Azure Key Vault doesn't support env variables  
<u><https://github.com/Azure/kubernetes-keyvault-flexvol/issues/28></u>

- I can't see secrets of Azure Key Vault which was created with terraform  
  (something wrong with access policies)
]

---
### Next Step

.zoom1[
- Continuous Delivery

  - Spinnaker, Argo CD, Tekton

- Service Mesh

  - Istio, SMI
]

---
### Source

<u><https://github.com/kyohmizu/mattermost-aks></u>

- Any ideas are appreciated!!

---
class: center, middle, blue
# Thank you!
