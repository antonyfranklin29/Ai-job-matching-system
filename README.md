AI-Powered Job Matching System

🚀 Overview
This project automates job searching using AI and web scraping. It matches job listings with my resume and provides direct application links.

📄 Project Description
This AI-powered job matching system integrates Claude AI with Apify API connectors to scrape job listings from multiple platforms and company career pages. The system analyzes my resume, semantically matches it with job descriptions, and returns curated results with direct application links. This reduces manual effort and improves job search efficiency.

🧠 Problem
Manual job searching is time-consuming and inefficient.

💡 Solution
Built an AI-powered workflow that:

* Scrapes job listings using Apify
* Matches them with my resume using Claude AI
* Provides direct job application links
  
🛠️ How It Works
1. User provides resume
2. Claude AI analyzes resume
3. Apify scrapes job platforms
4. AI matches jobs with resume
5. System filters relevant roles
6. Direct application links returned

🏗️ Architecture Diagram
This diagram shows the overall system components and their interactions.

<img width="1200" height="876" alt="Architecture" src="https://github.com/user-attachments/assets/c46b8715-8a5d-45b8-b157-b2e75bbefce9" />


🔄 Data Flow Diagram
This diagram illustrates how data moves from resume input to job recommendations.

<img width="1200" height="876" alt="Data Flow" src="https://github.com/user-attachments/assets/2364b1c3-c52b-4589-8f78-224b7147b9af" />


⚙️ Workflow Diagram
Step-by-step execution of the AI job matching process.

![AI_Job_Matching_Workflow](https://github.com/user-attachments/assets/3fe904d8-7570-4fed-b9f4-5deda95191ef)


🔗 Pipeline Diagram
End-to-end automation pipeline.

![Pipeline](https://github.com/user-attachments/assets/acde53a3-1a2a-4d76-bfb7-f73967f9c0b1)

⚙️ Tech Stack
• Claude AI (LLM)
• Apify API (Web Scraping)
• Prompt Engineering
• Job Platforms (LinkedIn, Indeed, Company Career Pages)

🔄 Workflow
Resume → Claude AI → Apify API → Job Listings → Filtered Results

📊 Features
* Automated job scraping
* AI-based matching
* Multi-platform search
* Direct apply links

📈 Impact
* Reduced job search time
* Improved job relevance

🔮 Future Improvements
* Build UI (web app)
* Add user login system
* Real-time alerts
