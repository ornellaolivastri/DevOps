# Automated VM Deployment with Terraform
Here I'll store my projects created to learn Infrastructure as Code (IaC) by automating the deployment of a Virtual Machine in Azure using Terraform.

---

## 🛠 What is Terraform?
**Terraform** is an open-source tool that allows you to define, provision, and manage cloud infrastructure using code instead of clicking through the cloud provider's console. 

Instead of writing step-by-step scripts (like Bash or PowerShell), you use a declarative language called **HCL (HashiCorp Configuration Language)** to describe the exact *end-state* of the infrastructure you want, and Terraform figures out how to build it safely.

---

## 🎯 Project Roadmap

This repository tracks my learning progress as I build out the following components step-by-step:
- [ ] **Phase 1: Setup & Auth** - Install Terraform & Azure CLI, and authenticate with my cloud provider.
- [ ] **Phase 2: Core Network** - Deploy a Resource Group, a Virtual Network (VNet), and a Subnet.
- [ ] **Phase 3: Security & IP** - Configure a Network Security Group (NSG) and allocate a Public IP address.
- [ ] **Phase 4: Compute** - Deploy the Ubuntu Virtual Machine and associate it with a Network Interface Card (NIC).
- [ ] **Phase 5: Output & Access** - Configure Terraform outputs to print the VM's public IP and test SSH access.

---

## 💻 Technical Prerequisites

To run this project locally, you need:
* An active **Azure Account** (Free tier works perfectly).
* **Terraform CLI** installed.
* **Azure CLI** installed.
