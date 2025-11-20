# 🎵 Personal Music Diary

A simple cloud-based app to track your daily mood and the song that represents your day.  
Built with Python, Flask and AWS.

## 🌬️ Project Idea

The Personal Music Diary lets you select a daily mood, add a Spotify track, and store everything in a cloud database.  
Your entries appear as a simple timeline of dates, moods, and songs.

Each entry includes:
- Date
- Mood tag (e.g. calm, focused, happy)
- Song title and Spotify link
- Optional image (album cover or custom photo)

## 🔭 Architecture Overview

**Frontend**
- Flask templates (HTML/CSS)
- Simple input form and timeline view

**Backend**
- Python (Flask)
- Spotify Web API for metadata
- PostgreSQL (local SQLite during development)
- Optional: S3 for image storage

**AWS (Phase 2)**
- EC2 for hosting the app
- RDS PostgreSQL for persistent storage
- S3 for images
- IAM roles and access control
- (Optional) CloudWatch logs

## 🗺️ Project Roadmap (MVP)

1. Create Flask app with input form  
2. Add local SQLite database  
3. Build a display page for timeline entries  
4. Add Spotify track search  
5. Replace SQLite with AWS RDS  
6. Deploy app on EC2  
7. (Optional) Image uploads to S3

Estimated time: 1–2 weeks (1–2 hours/day)

## 🐈‍⬛ Technologies & Skills Practiced

- Python + Flask
- SQL fundamentals
- Spotify Web API usage
- AWS (EC2, RDS, IAM, S3)
- GitHub workflows and versioning
- Debugging and logging

## 🪄 Stretch Features

- Mood graph (Chart.js or Plotly)
- User authentication (Cognito)
- Hybrid timeline and album-art view
- Containerization with Docker
- Terraform IaC deployment
- CI/CD pipeline in GitHub Actions

## 🌿 Status

This project is part of my ongoing post-internship learning path.  
Development begins November 2025.

Update: ![First UI Screenshot](docs/screenshots/Cloud-Music-Diary-SS-1.png)

## 🔮 Contact

Feel free to reach out or follow progress on GitHub.  
This project is part of my community space: Cat’s Cloud on Discord.
This text/project suggestion was created with Chat GPT. 
