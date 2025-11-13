# AWS Static Website Hosting – Travel Blog 🌍

## 📘 Project Overview
This project demonstrates how to **host a static website using Amazon S3** and **distribute it globally via CloudFront** for low-latency and high availability.

---

## 🧱 Website Setup
- Contains HTML, CSS, JS, and images only (no backend processing).
- Customized title: *Ishita's Travel Blog*.
- Hero section features a personalized background image (`hero.jpeg`).

---

## 🚀 Deployment Steps

### 1. Create an S3 Bucket
- Go to AWS Console → S3 → Create bucket.
- Bucket name: `ishita-static-website`
- Region: `ap-south-1`
- Uncheck **Block all public access**.
- Enable **Static website hosting** (Properties tab).
- Note down the **Bucket Website Endpoint**.

### 2. Upload Website Files
Upload all project files (`index.html`, `about.html`, `css/`, `js/`, `images/`, etc.)
or run:
```bash
aws s3 sync . s3://ishita-static-website --delete
