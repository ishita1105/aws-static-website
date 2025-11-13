### AWS Static Website Hosting – Travel Blog 🌍

A fully deployed static travel blog website hosted on Amazon S3 and distributed globally using Amazon CloudFront for fast, secure, and low-latency content delivery.

This project demonstrates foundational AWS skills including storage, caching, permissions, distribution, and public hosting — fulfilling all requirements of the Udacity Cloud DevOps program.

### 📘 Project Overview

This project showcases how to deploy a static website using:
Amazon S3 as the storage layer
CloudFront CDN for global content delivery
Proper bucket permissions and static hosting configuration
Public accessibility using both bucket endpoint and CloudFront URL
The website is built using plain HTML, CSS, and JavaScript and includes custom images, layouts, and responsive design elements.

### 🧱 Website Features

🌄 Custom hero banner (hero.jpeg)
🌐 Multi-page layout (Home, About, Gallery, etc.)
🎨 Clean design with CSS styling
📱 Responsive layout for mobile and desktop
⚡ Fast delivery through CloudFront caching
🗂️ Organized project folder structure

### 🌐 Public URLs
- S3 Bucket Website Endpoint
👉 <[http://my-722146899913-bucket.s3-website.us-east-2.amazonaws.com]>

-CloudFront Distribution Domain
👉 <[http://d37vjdrewn1bbc.cloudfront.net]>

Both URLs allow public access for evaluation and meet Udacity submission requirements.

### 🏗️ Architecture Diagram (Text-based)
          +-----------------------+
          |   User's Browser      |
          +-----------+-----------+
                      |
                      v
          +-----------------------+
          |  Amazon CloudFront    |
          | (Global CDN Cache)    |
          +-----------+-----------+
                      |
                      v
          +------------------------+
          | Amazon S3 Bucket       |
          | (Static Website Files) |
          +------------------------+
