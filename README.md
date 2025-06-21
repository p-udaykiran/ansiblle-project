# 🚀 Hands-on Project: Apache2 Deployment using Ansible

## 🧠 Objective
Install **apache2** and deploy a **static web app** on an **AWS EC2** instance using an **Ansible Playbook**.

---
📸 Output Screenshot

Once the playbook runs, Apache serves the static site from /var/www/html on your EC2 public IP. Your web app is live!

💻 Environment
🖥️ EC2 (Ubuntu Server)

⚙️ Ansible (Control Node)

📦 apache2 package

🌐 Static HTML/CSS website

📁 Project Structure
ansible-apache-deploy/
├── static-site/
│   └── index.html
├── playbook.yml
├── images/
│   └── firstplaybook.png
└── README.md
✅ How to Run
Configure your inventory file with EC2 public IP.

Run the playbook:
<bold>
ansible-playbook -i inventory playbook.yml
</bold>
Access your web app via EC2 public IP in the browser.
