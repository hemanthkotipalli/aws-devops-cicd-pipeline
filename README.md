1. Project Title
  # AWS CI/CD Deployment Pipeline (Docker + GitHub Actions + EC2)

2. Project Description
  ## 📖 Description
    This project demonstrates a complete CI/CD pipeline using GitHub Actions, Docker, and AWS EC2.

      Whenever code is pushed to GitHub, the pipeline automatically:
      - Builds a Docker image
      - Deploys it to an AWS EC2 instance
-      Runs the application inside a Docker container using Nginx

3. Tech Stack
    ## 🛠 Tech Stack
      - AWS EC2 (Ubuntu)
      - Docker
      - Git & GitHub
      - GitHub Actions (CI/CD)
      - Nginx
      - Linux

4. Architecture
    ## 🏗 Architecture Flow

 GitHub Push
     ↓
GitHub Actions (CI/CD Pipeline)
     ↓
Docker Build Image
     ↓
Deploy to AWS EC2
     ↓
Run Container (Nginx Web Server)
     ↓
Application Live on Port 8080

5. How to Run Locally
    ##  Run Locally

Clone the repository:

git clone https://github.com/your-username/aws-devops-cicd-pipeline.git

Move into project directory:

cd aws-devops-cicd-pipeline

Build Docker image:

docker build -t devops-project .

Run container:

docker run -d -p 8080:80 devops-project
## 🌐 Access Application

Open browser:

http://http://54.227.127.235/

7. CI/CD Pipeline Details
   ##  CI/CD Pipeline

1. Developer pushes code to GitHub
2. GitHub Actions triggers workflow
3. Docker image is built automatically
4. Image is deployed to EC2 instance
5. Container runs and application goes live

8. Project Structure
##  Project Structure

├── Dockerfile
├── index.html
├── style.css
├── .github/workflows/deploy.yml
└── README.md 

9. Key Learnings
   ## Key Learnings
- Docker containerization
- CI/CD automation using GitHub Actions
- AWS EC2 deployment
- Linux server management
- DevOps workflow automation

10. Author Section
  ## 👨‍💻 Author

Name: Your Name  
GitHub: https://https://github.com/hemanthkotipalli
