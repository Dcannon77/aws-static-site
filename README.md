# Daivene Static Site

A simple static website hosted on **AWS S3** and deployed via **GitHub Actions**.

## Features

- Static website hosted on **S3**
- Automated deployment with **GitHub Actions**
- Syncs local files to S3 bucket with `aws s3 sync`
- Cleans up old files in the bucket with `--delete` flag

## Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/Dcannon77/aws-static-site.git

