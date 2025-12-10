# 📘 Influencer Task Automation & Workflow Management System

This project is an automated influencer task management system built using **n8n**, **Google Sheets**, **Asana**, and **Gemini AI**. It processes influencer data, generates structured task details using AI, and automatically creates actionable tasks in Asana with due dates, priorities, and platform targeting.

The workflow removes manual coordination effort by integrating data extraction, AI processing, and task creation—ensuring fast, consistent, and scalable influencer campaign execution.

---

## 🚀 Key Capabilities

### ✅ 1. Automated Data Fetching
The system pulls influencer information directly from a Google Sheet:

- **Influencer Name**
- **Platform**
- **Followers**
- **Niche**
- **Engagement Rate**
- **Email**
- **Location**
- **Average Likes**

Each row becomes an input for automated task generation.

---

## 🤖 2. AI-Powered Task Generation (Gemini)

Influencer details are processed through **Gemini AI**, which:

- Generates a structured task JSON  
- Creates a relevant task title  
- Assigns a proper priority level  
- Selects the correct platform  
- Generates a due date (2–4 days from today)  
- Returns clean, validated JSON through a structured output parser  

This ensures fully consistent and formatted task data for every influencer.

---

## ⚙️ 3. Automated Task Creation in Asana

Once the AI generates task details, the system:

- Creates a new task in **Asana**
- Sets the correct name and title
- Applies the AI-generated priority
- Assigns an appropriate due date
- Attaches metadata for workflow tracking

Every influencer receives an actionable, ready-to-execute task with zero manual input.

---

## 🔁 4. Batch Processing & Looping

The workflow:

- Loops through all influencer rows
- Processes each item individually
- Limits execution when needed
- Ensures stable, scalable automation for large datasets

---

## 🧩 5. Modular Workflow Architecture

The system is built with clean, reusable modules:

- Manual Trigger  
- Google Sheets Data Fetcher  
- Batch Loop Handler  
- Gemini AI Task Generator  
- Structured Output Parser  
- Asana Task Creator  

Each module can be updated, replaced, or extended independently.

---

## 🔄 6. Fully Automated Execution Pipeline

Once the workflow is executed:

1. Influencer data is fetched from Google Sheets  
2. Each record enters the batching loop  
3. Gemini AI generates task details  
4. Validated output is parsed into JSON  
5. Asana tasks are created automatically  

No human involvement required.

---

## 🎯 Project Purpose

Built for:

- Social Media Teams  
- Influencer Marketing Agencies  
- Brand Campaign Managers  
- Workflow Automation Specialists  
- Multi-platform Content Teams  
