# Cloud-Native Telegram Bot for Content Moderation
> A group project to develop a cloud-native chatbot on Google Cloud Platform (GCP) that aggregates user-subscribed Telegram channel feeds and automatically filters advertisement messages.

##  Project Overview

Telegram is a popular messaging app, but users who subscribe to multiple channels often face cluttered feeds filled with spam and advertisements. This project aimed to solve this problem by creating a centralized "Telegram Feed" where users can view all their content in one place, powered by a chatbot that provides a clean, ad-free experience.

##  My Specific Contributions

Within the project team, I was solely responsible for the design and implementation of the **Ad-Detection Module**, which was the core feature for content moderation.

- **Module Design:** Architected the ad-detection service as an independent, containerized microservice.
- **Algorithm Implementation:** Utilized PySpark to process and analyze the plaintext of channel posts to identify and flag messages as advertisements based on defined heuristics.
- **Cloud Deployment:** Contributed to the deployment of our services on Google Cloud Platform (GCP), gaining hands-on experience with Cloud Run and containerization.

##  Architecture & Tech Stack

The system was built as a set of interconnected microservices deployed on GCP. Here is the high-level system diagram:

![System Diagram](./[请在这里上传您PPT里的系统架构图并替换文件名].png)

**Tech Stack:**
- **Languages:** Python
- **Data Processing:** PySpark
- **Cloud Platform:** Google Cloud Platform (GCP)
- **Services:** Cloud Run, Cloud SQL (PostgreSQL), Artifact Registry, Docker
- **APIs:** Telegram Bot API

## Presentation

For a complete overview of the system architecture, design choices, and a visual demonstration, please see our final presentation slides.

 **[View Final Presentation (PDF)](./Telegram%20Feed.pdf)**

## Team

This project was a collaborative effort. My teammates were: Evgenii Venediktov, Dilip Teja, Dominick Dellecave, Thomas Noto
