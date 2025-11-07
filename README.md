# Azure Identity & Access Automation

This project automates the setup of secure identity and access controls in Azure using **Azure CLI** and **Bash scripting**.

## 🚀 Tasks Automated
1. Create a resource group, virtual network, and two subnets (Web and DB).
2. Create Azure AD groups: `WebAdmins` and `DBAdmins`.
3. Assign Reader role to `DBAdmins` for DB subnet resources.
4. Add test users to the AD groups and validate role assignments.

## 📦 How to Use
1. Clone this repo:
   ```bash
   git clone https://github.com/Veekeebliss/Capstone
   cd Capstone
