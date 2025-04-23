# Static Website Deployment to AWS S3 via GitHub Actions

This project demonstrates how to automatically deploy a static website (HTML, CSS, JS) to an AWS S3 bucket using GitHub Actions for continuous deployment.

## 🚀 Overview

The setup includes:
- Hosting a static website using AWS S3
- Automatically deploying changes pushed to GitHub
- Simple configuration using GitHub Secrets and a deploy workflow

## ✅ Prerequisites

- AWS account
- GitHub account
- Static website files (HTML, CSS, JS)
- AWS CLI installed locally (for initial setup)

## 🔧 Setup Instructions

### 1. Create an S3 Bucket
- Make a new bucket (name must be globally unique)
- Enable static website hosting under **Properties**
- Set `index.html` as the index document
- Update **Permissions** with a public read policy


### 2. Add GitHub Secrets
- Go to your repo → Settings > Secrets and variables > Actions, and add:

- AWS_ACCESS_KEY_ID

- AWS_SECRET_ACCESS_KEY

- AWS_S3_BUCKET

- AWS_REGION