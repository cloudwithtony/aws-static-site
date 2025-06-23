# 🌐 AWS Static Website Portfolio

Fully serverless static site hosted on **Amazon Web Services** now with **GitHub Actions CI/CD**.

## 🚀 Live Site  
➡️ https://d2ogr6k8pmoty.cloudfront.net

## 🛠 Tech Stack
| Service | Purpose |
|---------|---------|
| **Amazon S3** | Stores static assets (`index.html`, `style.css`) in a private bucket |
| **AWS CloudFront** | Global CDN with HTTPS + custom 403/404 pages |
| **Origin Access Control** | Locks the S3 bucket so only CloudFront can read |
| **GitHub Actions** | Auto-deploys on every `git push` (`aws s3 sync` + cache invalidation) |
| **IAM** | Least-privilege policy for the CI pipeline |

## 📦 Key Features
- 🔒 HTTPS + private-bucket security  
- ⚡ One-click auto-deploy via GitHub Actions (`deploy.yml`)  
- 🛠 Custom error pages (403/404)  
- 🆓 100 % Free-Tier compliant  

## 💡 What I Learned
- Building secure static sites on AWS (S3 + CloudFront + OAC)  
- Writing IAM policies & bucket policies  
- Creating CI/CD pipelines with GitHub Actions  
- Troubleshooting permissions, cache, and routing

## 🧑‍💻 Author
**Anthon Sonnier** — Houston, TX  
📧 [Anthon.sonnier@gmail.com](mailto:Anthon.sonnier@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/anthon-sonnier-6028211a3)

