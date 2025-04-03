# vault-wordpress-packer-project



markdown
# 🔐 Secrets Management with Vault & WordPress Setup using Packer and Vagrant

This project demonstrates how to use **HashiCorp Vault** for secrets management by setting up two virtual machines using **Packer** and **Vagrant** on a Mac M1.



## 📦 Project Overview

The setup involves:

- Creating two Ubuntu 22.04 virtual machines using Packer:
  - **VM1**: Vault server setup
  - **VM2**: WordPress server pulling secrets from Vault



## 🧱 Technologies Used

- HashiCorp **Packer**
- **Vagrant**
- **Vault**
- **Ubuntu 22.04**
- **WordPress**
- Shell scripts and provisioning
- Mac M1 terminal setup



## ⚙️ What I Did (Steps Summary)

1. **Built a custom Ubuntu box using Packer** and initialized it with Vagrant.
2. **Installed Vault** and configured it on the first VM with secure TLS settings.
3. **Enabled the KV v2 secrets engine**, created policies, tokens, and stored secrets (DB credentials, SSH passwords).
4. **Created a second VM with WordPress**, used Packer to install it automatically with a provisioning script.
5. **Connected the WordPress VM to Vault** using environment variables to fetch secrets securely.
6. **Accessed WordPress in the browser**, verified that everything worked, and created a blog post.



## 🌐 Output

You can find all steps and screenshots in the markdown file `project-steps.md` inside this repository.



## 📁 Files

- `project-steps.md`: Full step-by-step documentation with screenshots
- 'Images folder': Output screenshots for Part 1, 2, and 3



## 🚀 Outcome

✅ Successfully demonstrated integration of secure secrets management using Vault with an automated WordPress deployment on two VMs using Packer and Vagrant.

