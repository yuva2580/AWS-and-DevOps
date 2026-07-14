# AWS Online Examination System

## Project Overview
The AWS Online Examination System is a web-based application that allows students to take online exams and enables administrators to manage questions, students, and results. The project is deployed on AWS using a secure 3-tier architecture.

## Features
- Student Login
- Admin Login
- Upload Questions
- Random Question Generation
- Timer-Based Exam
- Auto Submit
- Score Calculation
- Answer Key
- Leaderboard
- PostgreSQL Database

## Technologies Used
- Python
- Flask
- HTML
- CSS
- JavaScript
- PostgreSQL
- AWS EC2
- AWS RDS
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Route 53
- AWS Certificate Manager (ACM)
- Nginx
- Gunicorn
- Git & GitHub

## AWS Architecture

Users
↓
Route 53
↓
AWS Certificate Manager (SSL)
↓
Application Load Balancer
↓
EC2 Instances (Flask + Gunicorn + Nginx)
↓
Amazon RDS PostgreSQL

## Project Structure

```
AWS-and-DevOps/
├── app.py
├── templates/
├── static/
├── requirements.txt
├── README.md
└── ...
```

## Installation

```bash
git clone https://github.com/yuva2580/AWS-and-DevOps.git

cd AWS-and-DevOps

pip install -r requirements.txt

python app.py
```

## Future Improvements
- Email Notifications
- AI-Based Proctoring
- Mobile-Friendly UI
- Exam Analytics Dashboard

## Author

**Yuvaraj Pujari**

GitHub: https://github.com/yuva2580
