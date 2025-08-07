☁️ Static Website Hosting on AWS
Proof of concept: DO NOT USE IN PRODUCTION
🔍 Overview
Deployed a secure, globally accessible static website using Amazon S3, CloudFront, and Route 53. This project demonstrates modern cloud hosting practices for static content.

🧠 Key Skills Demonstrated
S3 bucket creation & configuration


Static website hosting with S3


Domain configuration with Route 53


Content distribution using CloudFront CDN


Basic DNS management & SSL with ACM



🛠️ Tools Used
AWS S3


AWS Route 53


AWS CloudFront


AWS Certificate Manager (ACM)


Custom domain from Namecheap (or any provider)



🧱 Architecture Diagram



⚙️ Setup Steps
Create an S3 bucket (public access, static hosting enabled)


Upload website files (HTML, CSS, etc.)


Set up CloudFront distribution (pointed to the S3 bucket)


Request SSL certificate using ACM


Set up custom domain with Route 53 (or any DNS provider)


Connect domain to CloudFront using alias records



✅ Outcome
A fully functional, secure static website hosted on AWS with global performance via CDN and HTTPS encryption.

🔧 Possible Future Improvements
Automate deployments using AWS CDK or Terraform


Add CI/CD with GitHub Actions


Add versioning and lifecycle rules to S3


Use WAF for security filtering on CloudFront


Add analytics or monitoring via CloudWatch
