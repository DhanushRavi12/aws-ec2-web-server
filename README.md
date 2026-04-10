# 🚀 AWS EC2 Web Server Deployment

## 📌 Project Overview
This project demonstrates how to launch an AWS EC2 instance and deploy a web server using Apache on Amazon Linux.

---

## 🔧 Technologies Used
- AWS EC2
- Amazon Linux
- Apache (httpd)
- Security Groups
- SSH (EC2 Instance Connect)

---

## ⚙️ Architecture
User → Internet → EC2 Instance → Apache Web Server

---

## 🚀 Steps Performed

### 1️⃣ Launch EC2 Instance
- Selected Amazon Linux AMI
- Instance type: t3.micro
- Enabled public IP
- Configured key pair

### 2️⃣ Configure Security Group
- Allowed SSH (Port 22)
- Allowed HTTP (Port 80)

### 3️⃣ Connect to EC2
- Used EC2 Instance Connect

### 4️⃣ Install Apache
```bash
sudo yum update -y
sudo yum install httpd -y

## 👨‍💻 Author

**Dhanush R**  
🚀 AWS & DevOps Enthusiast  

📧 r.dhanushravii1202@gmail.com  
📞 +91 9080414681  

🔗 LinkedIn: https://www.linkedin.com/in/dhanush-ravi-934784232/  
💻 GitHub: https://github.com/DhanushRavi12
