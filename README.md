# CloudCompliance-Lab
[![Use this template](https://img.shields.io/badge/-Use%20this%20template-brightgreen?style=for-the-badge)](https://github.com/Watchcat25/CloudCompliance-Lab/generate)

[![Terraform](https://img.shields.io/badge/IaC-Terraform-blueviolet)](https://www.terraform.io/)
[![Validation Ready](https://img.shields.io/badge/Validation-GxP%20Compliant-green)]()
[![Cloud](https://img.shields.io/badge/Cloud-AWS%20%7C%20Azure-orange)]()

This project shows how to build and validate a cloud setup that meets GxP compliance requirements using AWS and Azure.

It’s designed for environments like healthcare or pharma, where systems must follow strict rules to protect data and ensure safety.


---

**What This Lab Covers**

This lab simulates a full validation workflow:

✅ Building cloud infrastructure with Terraform

✅ Creating and testing GxP-compliant environments

✅ Using standard validation templates (IQ/OQ/PQ)

✅ Managing risks and change requests

✅ Automating tasks using PowerShell and GitHub Actions

You’ll get a full view of what it takes to deploy cloud services the right way in regulated industries.


---

## 📁 Project Structure

| Folder | Description |
|--------|-------------|
| `terraform/` | Infrastructure as Code for AWS and Azure |
| `validation/` | IQ/OQ/PQ plans, logs, and screenshots |
| `compliance/` | Risk mapping and change request templates |
| `scripts/` | PowerShell and Bash automation |
| `.github/` | GitHub Actions workflow for CI/CD |

---

✅ Validation Evidence
1. Installation Qualification (IQ)

Command: terraform init
Purpose: Initialize Terraform providers.
Command: terraform validate
Purpose: Validate that configuration is syntactically correct.

Result: ✅ Success - Configuration is valid.

Screenshot:
<img width="1919" height="299" alt="I!_terraform_init_validate" src="https://github.com/user-attachments/assets/a7cd428c-b6db-42dc-b45d-329e5d5ab403" />


## 🚀 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/Watchcat25/CloudCompliance-Lab.git
