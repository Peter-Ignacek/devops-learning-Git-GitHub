## 🚀 Environment Setup

- Git installed and configured on Windows (local development)
- Git installed on AWS EC2 instance (Amazon Linux)
- SSH key-based authentication configured
- Remote server access via SSH

## ☁️ AWS Lab

- Platform: Amazon Web Services (EC2)
- OS: Amazon Linux
- User: ec2-user
- Authentication: SSH key (no password login)

## 🛠️ Tools

- Git
- GitHub
- AWS EC2
- Linux (Amazon Linux)

## 📦 Git Installation (Amazon Linux)
````
sudo su -
````
Installation performed using package manager:
````?
yum install git
````


## 👤 Git Configuration

Set global Git identity:

```bash
git config --global user.name "Piotr"
git config --global user.email "piotr@ignacek.com"
````
## 🔍 Verify Configuration
````
git config --global user.name
git config --global user.email
````
## 🔍 Git Configuration Check

Display current Git configuration:

```bash
git config --list
````
<img width="572" height="374" alt="image" src="https://github.com/user-attachments/assets/5f686283-e932-4008-8d5d-a4d9c8f963c4" />

