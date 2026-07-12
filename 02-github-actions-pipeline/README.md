# Learning CI/CD: Automating Infrastructure with GitHub Actions

This is a 100% learning-focused repository. My goal here is to bridge the gap between manual workflows and modern DevOps automation by exploring how to build a CI/CD pipeline from scratch. 

I am documenting my progress step-by-step as I study these tools and learn how to implement them.

---

## 🚀 Concepts & Tools I am Exploring
As I progress through this project, I am researching and getting hands-on practice with:
* **CI/CD Fundamentals** (Continuous Integration & Continuous Deployment)
* **GitHub Actions** (Workflows, Runners, Actions, and Secrets management)
* **YAML syntax** for pipeline configuration
* **Automated Infrastructure as Code (IaC)** with Terraform

---

## 🎯 My Learning Roadmap (Step-by-Step)

I created this checklist to map out the technical milestones I want to learn, test, and master:

- [ ] **Phase 1: Workflow Basics** - Learn how to create a basic GitHub Actions workflow (`.github/workflows/deploy.yml`) to understand how triggers and runner environments work.
- [ ] **Phase 2: Azure Secrets Management** - Research how to securely store Azure cloud credentials inside GitHub Repository Secrets to authenticate the pipeline safely without exposing keys.
- [ ] **Phase 3: Automated Terraform Execution** - Experiment with configuring the pipeline to automatically trigger `terraform init`, `terraform plan`, and `terraform apply` workflows upon code pushes.
- [ ] **Phase 4: Sample App Deployment** - Take on the challenge of adding a simple application into the repository and automating its delivery into the provisioned Azure infrastructure.
- [ ] **Phase 5: Automated Cleanup** - Implement a manual pipeline trigger to run `terraform destroy` so I can learn how to efficiently tear down cloud environments.

---

*Note: This repository is a constant work in progress and serves as a personal log of my technical growth and evolution.*
