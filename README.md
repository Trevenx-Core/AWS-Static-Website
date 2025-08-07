# ☁️ Static Website Hosting on AWS (Proof of Concept)
> **⚠️ Note:** This project is for demonstration purposes only — **DO NOT USE IN PRODUCTION**.

---

## 🔍 Overview
This project demonstrates deploying a **secure, globally accessible static website** using **Amazon S3**, **CloudFront**, and **Route 53**.  
It follows modern cloud hosting practices for static content distribution and HTTPS encryption.

---

## 🧠 Key Skills Demonstrated
- **S3 bucket creation & configuration**
- **Static website hosting** with S3
- **Domain configuration** with Route 53
- **Content distribution** using CloudFront CDN
- **Basic DNS management & SSL** with ACM

---

## 🛠️ Tools Used
- **AWS S3**
- **AWS Route 53**
- **AWS CloudFront**
- **AWS Certificate Manager (ACM)**
- Custom domain from **Namecheap** (or any provider)

---

## 🧱 Architecture Diagram
TBD

---

## ⚙️ Setup Steps
1. **Create an S3 bucket**  
   - Enable public access  
   - Enable static website hosting  

2. **Upload website files**  
   - HTML, CSS, JS, images, etc.

3. **Set up CloudFront distribution**  
   - Point to the S3 bucket as the origin

4. **Request SSL certificate**  
   - Use AWS Certificate Manager (ACM)

5. **Set up custom domain**  
   - Use Route 53 (or any DNS provider)

6. **Connect domain to CloudFront**  
   - Use **alias records** in Route 53

---

## ✅ Outcome
A fully functional, **secure static website** hosted on AWS with:
- **Global performance** via CloudFront CDN
- **HTTPS encryption** using ACM
- **Custom domain integration**

---

## 🔧 Possible Future Improvements
- Automate deployments using **AWS CDK** or **Terraform**
- Add CI/CD with **GitHub Actions**
- Add **versioning** & **lifecycle rules** to S3
- Use **AWS WAF** for security filtering
- Add **analytics or monitoring** via CloudWatch

---

## 📜 License

Add CI/CD with GitHub Actions


Add versioning and lifecycle rules to S3


Use WAF for security filtering on CloudFront


Add analytics or monitoring via CloudWatch
