
# 🚀 10 Days of GitHub Actions

Welcome to the **10 Days of GitHub Actions** series!  
This is a hands-on journey to master CI/CD using GitHub Actions — from the basics to deploying apps on AWS.

Whether you're a beginner or a dev looking to automate your workflow, this repo will guide you step-by-step with real examples, diagrams, and deployment scripts.

---

## 📅 What You'll Learn

| Day | Topic |
|-----|-------|
| 1️⃣ | Introduction to GitHub Actions & Your First Workflow |
| 2️⃣ | Workflow Anatomy – Jobs, Steps, Runners |
| 3️⃣ | GitHub-Hosted vs Self-Hosted Runners |
| 4️⃣ | Running GitHub Actions Locally (`act`) |
| 5️⃣ | Using Secrets & Caching in Workflows |
| 6️⃣ | Build and Push Docker Images to AWS ECR |
| 7️⃣ | Deploy to AWS EC2 with GitHub Actions |
| 8️⃣ | Deploy a Static Site to AWS S3 + CloudFront |
| 9️⃣ | CI/CD with AWS ECS (Fargate) |
| 🔟 | Reusable Workflows, Matrix Builds & Final Wrap-Up |

---

## 📂 Repository Structure

```bash
.
├── .github
│   └── workflows          # All workflow YAML files
├── docs
│   └── day-01.md to day-10.md  # Learning notes per day
├── flows
│   └── diagrams           # Drawings and architecture flows
├── aws-scripts
│   └── deploy.sh, ecs.json, etc.
├── app/                   # Sample app for testing CI/CD
└── README.md
```

---

## 📺 Follow the Series

Each day includes:
- ✅ GitHub commit with code & workflow
- 🎥 YouTube video walkthrough
- ✍️ LinkedIn carousel/post for deeper explanation

### 📌 YouTube Playlist: [Coming Soon](#)
### 📌 LinkedIn Posts: [#10DaysOfGitHubActions](https://linkedin.com)

---

## 🛠 Prerequisites

- A GitHub account
- Basic terminal/Git knowledge
- AWS account (for deploy days)
- Docker installed (optional but useful)
- Node.js or Python installed (depending on sample app)

---

## 🔐 AWS Credentials Setup (for Days 6-9)

Store these as GitHub Secrets:

| Secret Name | Description |
|-------------|-------------|
| `AWS_ACCESS_KEY_ID` | Your AWS Access Key |
| `AWS_SECRET_ACCESS_KEY` | Your AWS Secret Key |
| `AWS_REGION` | e.g., `us-east-1` |

---

## 🙌 Contributing

Want to improve this repo or translate it? Feel free to open issues or pull requests!

```bash
git clone https://github.com/yourusername/10-days-of-github-actions.git
cd 10-days-of-github-actions
```

---

## 📜 License

MIT License.  
You can copy, remix, or use any workflow shown here. Just give credit where it's due. 💛

---

## 👋 Stay Connected

Follow me on:
- **LinkedIn**: [Muhammed Rashid](https://www.linkedin.com/in/muhammad-rashid-daha/)
- **YouTube**: [CodeWithMuh](https://youtube.com/@codewithmuh)
- **LinkedIn NewsLetter**: [@codewithmuh](https://www.linkedin.com/in/muhammad-rashid-daha/)

---

Let’s automate everything — one push at a time. ✨
