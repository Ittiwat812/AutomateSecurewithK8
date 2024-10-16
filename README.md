# Kubernetes Configuration Manager

## Overview

This project introduces an innovative application designed to enhance the security of Kubernetes pods by automating security configurations across multiple Dockers using Kubernetes. The application focuses on critical security areas including Isolation, Role-Based Access Control (RBAC), and Ingress-Specific IP controls, establishing a robust security posture for Kubernetes deployments.


## Main
- [Link for Download](https://www.dropbox.com/scl/fo/zltqsche3d7mf559z5o7l/ADuYvkEqBfLAs8WowfkuUPk?rlkey=agye9f90sztqk70g93nstmx2a&st=eqiqw6hp&dl=0)


## Features

- **Granular Isolation**: Prevent unauthorized access between pods, reducing the attack surface.
- **Dynamic RBAC**: Manage access permissions within pods through dynamic RBAC policies.
- **Ingress-Specific IP Policies**: Regulate ingress traffic between pods to minimize security risks.
- **Data Encryption**: Encrypt communications between pods and between pods and the cloud.

## Prototype

The Kubernetes Pod Configuration Manager allows users to select pods from a dropdown menu and apply various security configurations. Options include isolating selected pods, and controlling ingress traffic from specific IPs (Restricting root access is developing).

## Security Analysis

The system model secures a Kubernetes environment by focusing on policy enforcement, RBAC, and encrypted communication. It utilizes TLS for data security and integrity.

## How to Use

1. **Selecting a Pod**: Choose a pod from the dropdown menu in the Kubernetes Pod Configuration Manager.
2. **Applying Configurations**: Apply security configurations such as isolation, non-root access, and ingress controls.
3. **Observing Changes**: Use the terminal output within the GUI to verify the changes.

## Installation

```bash
git clone https://github.com/your-repository/kubernetes-config-manager.git
cd kubernetes-config-manager
```

# Dependencies
- Kubernetes Cluster
- Access to Kubernetes API
- Suitable network policies enabled

# Documentation
Further documentation is available at:
- [Kubernetes Official Documentation](https://kubernetes.io/docs/home/)
- [Network Policy Recipes](https://github.com/ahmetb/kubernetes-network-policy-recipes)
  
# Contributions

-  [Thanapat Thaipakdee](https://github.com/Nameister)
-  [Sirapitch Boonyasampan](https://github.com/titlesirapitch)

## Instructor

- **Dr. Somchart Fugkaew** - Adivsor.

## License

This project is licensed under the Sirindhorn International Institute of Technology (SIIT), Thammasat University. All rights reserved.
