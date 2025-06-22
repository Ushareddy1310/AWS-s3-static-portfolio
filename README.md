# Scalable Static Website with S3 + Cloudflare + GitHub Actions

This project demonstrates a scalable and automated deployment pipeline for a static portfolio website using **Amazon S3**, **GitHub Actions**, and (optionally) **Cloudflare**.

## 🌐 Live Demo
[Click to View Site](http://static.website-hosting.s3-website.ap-south-1.amazonaws.com)

## 🛠️ Tools Used
- **Amazon S3** – for static website hosting
- **GitHub Actions** – for CI/CD pipeline
- **IAM** – to securely allow deployment from GitHub
- **Git & GitHub** – version control and repo management
- **Cloudflare** – for CDN, HTTPS, and caching

## ⚙️ How It Works
- Website files (HTML, CSS) are stored in this repository
- A GitHub Actions workflow is triggered on every push to `main`
- The workflow uses AWS credentials (stored in GitHub Secrets) to sync the site to an S3 bucket
- Users can access the site via the S3 website endpoint

## 📁 Structure
- .github/workflows/deploy.yml ← GitHub Actions CI/CD pipeline
- index.html ← Main webpage
- style.css ← Styling

## 🔐 Security Notes
- AWS credentials are never stored in code  
- GitHub Secrets securely handle IAM keys

## 🚀 Final Thoughts

This project reflects a real-world DevOps use case — deploying a static website with scalable architecture and automation.  
It combines cloud technologies and CI/CD practices to deliver reliable, fast, and secure web experiences.  
Feel free to explore, fork, or build upon it!

---

✨ Built with ❤️ by Usha Reddy

