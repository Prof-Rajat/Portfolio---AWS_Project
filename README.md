# AWS Static Portfolio Hosting
A professional single-page portfolio hosted on AWS using a secure, scalable architecture.

## 🚀 Live Demo
https://d2zq8pkre0ess9.cloudfront.net

## 🛠️ Architecture
- **Storage:** Amazon S3 (Static Website Hosting enabled)
- **CDN:** Amazon CloudFront (for HTTPS and global delivery)
- **Security:** S3 Bucket Policies for restricted public access

## 📖 Steps Taken
1. Created an S3 bucket and enabled static hosting.
2. Uploaded frontend assets (HTML/CSS).
3. Configured S3 Bucket Policy to allow `s3:GetObject` for the public.
4. Created a CloudFront Distribution to serve content over HTTPS.

## 🧠 Key Learnings
- Cloud storage fundamentals and bucket permissions.
- Content delivery networks (CDNs) and SSL/TLS encryption.
- AWS Billing & Budgets (Set up a $0 alarm to monitor costs).