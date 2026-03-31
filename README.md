# Personal Portfolio Website - Oluwatunmise

Welcome to my personal portfolio website! This project showcases my cloud engineering projects, skills, and certifications, deployed on a production-ready AWS EC2 instance with CI/CD automation using GitHub Actions.

## 🌐 Live Site

[View Live Portfolio](http://3.84.151.174)  <!-- Replace with your EC2 public URL if needed -->

## 🛠️ Tech Stack

- **Cloud & Hosting:** AWS EC2, Nginx
- **CI/CD:** GitHub Actions for automatic deployment
- **Web:** HTML, CSS, JavaScript
- **Assets:** Self-hosted images and badges for certifications

## 💼 Projects Highlighted

- **AWS Certifications Badges:** Display of AWS Cloud Practitioner and AWS Solutions Architect Associate
- **Portfolio Sections:** Overview of cloud projects, scripts, and personal projects
- **Responsive Design:** Fully functional and accessible from any modern browser

## 🚀 Features

- Automatic deployment to AWS EC2 on every push to `main` branch
- Secure SSH setup using GitHub Actions Secrets
- Static website served through Nginx for high availability
- Organized assets folder for images, badges, and scripts

## 📁 Repository Structure
.
├── assets/                # Images, badges, and other assets
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions CI/CD workflow
├── index.html             # Main landing page
├── script.js              # JavaScript interactivity
└── style.css              # Styling for portfolio

## 🔒 Security & Best Practices

- CI/CD uses encrypted SSH keys stored in GitHub Secrets
- Deployment ensures only necessary files are copied to EC2
- Portfolio follows basic web security and performance best practices

## ✨ Author

**Oluwatunmise** – Cloud Engineer | AWS Certified Solutions Architect Associate  
[GitHub Profile](https://github.com/Oluwatunmise019)
