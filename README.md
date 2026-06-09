# DevOps Project 2026 🚀

## Project 1 — Stripe Payment App Deployed to AWS EC2

### What I Built
A Node.js payment application using Stripe,
deployed to a live AWS EC2 server.

### Tech Stack
- Node.js & Express
- Stripe Payment Integration
- AWS EC2 (Ubuntu)
- PM2 Process Manager
- Docker

### What I Learned
- SSH into a remote cloud server
- Deploy a Node.js app to EC2
- Manage processes with PM2
- Secure environment variables with .env
- Open ports in AWS Security Groups
- Clean secrets from Git history
- Push code to GitHub

### Project Structure

AWS-Session/
├── server.js        # Main application
├── client/          # Frontend files
├── Dockerfile       # Container config
├── package.json     # Dependencies
└── .env             # Secret config (not committed)

### How to Run Locally
```bash
npm install
npm run start
```

### How to Run with Docker
```bash
docker build -t stripe-app .
docker run -p 3000:3000 stripe-app
```

### Live Server
Running on AWS EC2 at http://13.51.163.1:3000
