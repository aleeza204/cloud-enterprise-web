# Cloud Enterprise App (Mini Project)

## 🌐 Overview
A small enterprise-style web app hosted on Huawei Cloud with ECS, RDS, EIP, NAT Gateway, and proper networking.

## 🧱 Architecture
- ECS (Elastic Cloud Server)
- RDS (MySQL)
- EIP (Public IP for ECS)
- NAT Gateway (for internet access)
- VPC & Security Groups (for secure networking)

## 📷 Screenshots
(see ./screenshots folder)

## ⚙️ How to Deploy
1. Create VPC, subnets, NAT Gateway
2. Launch ECS instance with EIP
3. Deploy this website
4. Create RDS MySQL instance
5. Configure security groups to allow ECS → RDS
6. Connect app to RDS (if dynamic)
7. Test in browser

## 🖼️ Screenshots
- ECS setup  
- EIP bind  
- RDS MySQL  
- NAT Gateway  
- Web app running

## 🔗 Live Demo
[http://YOUR_EIP](http://190.92.209.192/wordpress/wp-admin/)

## 👤 Author
Jasim ALI | [LinkedIn](https://www.linkedin.com/in/aleeza-shehzadi-201a7136a)
