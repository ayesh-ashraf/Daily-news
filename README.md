
# Scheduled Optometry News – n8n Automation Workflow

### Automate your daily optometry news updates with AI-powered
##  Overview

**Scheduled Optometry News** is an automation workflow built in **n8n** that automatically fetches the latest optometry news from an RSS feed, summarizes it using an AI model, and sends a neatly formatted daily email to the recipient.

This workflow saves time for optometrists, students, and healthcare professionals who want to stay informed about new research and industry developments without manually checking multiple sources every day.

##  Purpose
> To create an automated, AI-enhanced system that collects, summarizes, and delivers the latest optometry-related news directly to your inbox at a scheduled time.

## Workflow Structure
Below is the breakdown of all nodes and their purpose:


 **RSS Feed Trigger** : Automatically pulls the latest news articles from an optometry-related RSS feed (e.g., *Optometry Today*, *Modern Optometry*). 
 **Loop Over Items**  : Iterates through every news article fetched by the trigger. 
 **Message a Model (AI Node)** :  Uses an AI model to generate concise summaries or key takeaways from each article. 
 **Replace Me**  :A modular point for adding extra features like filtering, translation, or topic tagging. 
 **Merge Node** : Merges original article information with AI-generated summaries into one clean dataset. 
 **Send a Message (Email Node)** : Sends the summarized articles to the recipient’s inbox using Gmail or any configured email service.

##  Why This Workflow Matters

Professionals and students often lack time to browse multiple platforms for updates.  
This workflow functions as a **personal optometry newsletter generator**, reducing manual effort and ensuring continuous learning.  

It’s a demonstration of how **automation and AI** can streamline information flow in healthcare.

##  Customization Options

This workflow isn’t limited to academic news — it can be adapted for multiple purposes:

 *Healthcare Professionals* : Receive daily updates from specific medical specialties.
 *Students / Researchers* :Get AI-summarized research papers or journal updates.
 *Social Media Managers* : Auto-generate content ideas or captions.
 *Clinic Owners / Admins* : Send daily clinic reports to staff. 
 *Editors / Journalists* : Aggregate and summarize multi-source news feed. 


##  Setup Instructions

### 1. Clone the Repository
### 2. Open n8n :Launch your n8n instance and import the provided workflow JSON file.

### 3. Configure Environment
Add your RSS Feed URL (e.g., https://www.optometrytimes.com/rss)
Add your AI API Key (OpenAI, Gemini, etc.)
### 4. Connect your Email Credentials in the “Send a Message” node.

### 5. Schedule Automation
Use n8n’s Schedule Trigger .
### 6: Execute and Test
Click Execute Workflow and check your inbox for the summarized email.


### **Video Demonstration**
[Watch the full video here](https://youtu.be/Pb32NrFVapE)

### **Author**
Ayesha Ashraf



