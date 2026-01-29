# Terraform on Azure – Hands-On Lab Exercises 🚀

Welcome to the **Terraform_Azure** repository!  
This repository is designed to help you **learn Terraform by doing**, with practical **hands-on lab exercises focused on Microsoft Azure**.

Whether you are a **beginner starting with Infrastructure as Code (IaC)** or an **engineer preparing for real-world cloud projects**, this repo will guide you step by step.

---

## 📌 What You Will Learn From This Repository

By working through these labs, you will learn:

- What Terraform is and **why it is used**
- How Terraform works with **Azure (azurerm provider)**
- Writing Terraform code using:
  - Providers
  - Resources
  - Variables
  - Outputs
- Managing infrastructure lifecycle:
  - `terraform init`
  - `terraform plan`
  - `terraform apply`
  - `terraform destroy`
- Creating and managing Azure resources using Terraform
- Best practices for structuring Terraform projects

---

## 🧱 Repository Structure (High Level)

Each lab in this repository is focused on **one concept at a time**, keeping learning simple and practical.

Typical labs include:
- Terraform installation & setup
- Azure provider configuration
- Resource Group creation
- Virtual Machine creation
- Networking components
- Variables & outputs
- State management basics

👉 Each folder contains Terraform files (`.tf`) that you can run directly.

---

## ⚙️ Prerequisites

Before starting the labs, make sure you have:

- An **Azure account**
- **Azure CLI** installed and logged in  
  ```bash
  az login
