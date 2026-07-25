# 🤖 AI Meeting Action Tracker

> AI-powered meeting intelligence built on ServiceNow using Google Gemini 3.5 Flash.

![ServiceNow](https://img.shields.io/badge/ServiceNow-Enterprise-green)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES12-yellow)
![REST API](https://img.shields.io/badge/REST-Integration-orange)

---

## 📌 Overview

AI Meeting Action Tracker is a custom ServiceNow application that automatically analyzes meeting transcripts using Google Gemini 3.5 Flash.

The application transforms lengthy meeting transcripts into structured business insights by automatically generating:

- 🤖 AI-generated meeting summaries
- 📋 Automatic action item extraction
- ⚡ Task prioritisation
- 📊 AI processing logs
- 📈 Dashboard analytics

Built entirely on the ServiceNow platform using server-side JavaScript and REST API integrations.

---

## ✨ Features

- AI-generated Meeting Summaries
- Automatic Action Item Extraction
- Google Gemini 3.5 Flash Integration
- Async Business Rule Processing
- Service Catalog Record Producer
- AI Meeting Workspace
- Executive Dashboard
- AI Process Logs
- Manual Generate AI Action

---

## 🏗️ Architecture

```text
Service Catalog
        │
        ▼
Record Producer
        │
        ▼
Meeting Record
        │
        ▼
Async Business Rule
        │
        ▼
MeetingAIProcessor
        │
        ▼
Google Gemini 3.5 Flash
        │
 ┌──────┼──────────┐
 ▼      ▼          ▼
Summary Tasks   AI Log
        │
        ▼
 Dashboard
```

---

## 🎥 Demo

The repository includes a complete walkthrough of the application.

**Location**

```text
demo/AI_Meeting_Action_Tracker_ServiceNow_Gemini_Demo.mp4
```

You can watch the demo directly from GitHub.

---

## 🛠 Tech Stack

- ServiceNow
- JavaScript (ES12)
- GlideRecord
- Script Includes
- Async Business Rules
- RESTMessageV2
- Google Gemini 3.5 Flash
- Workspace
- Dashboards

---

## 🚀 Installation

1. Clone this repository.
2. Import the ServiceNow application.
3. Create the following System Property:

Name:

```
x_1908237_ai_mee_0.gemini_api_key
```

4. Set its value to your Google Gemini API Key.
5. Submit a meeting using the Record Producer.
6. AI processing begins automatically.

---

## 📂 Repository Structure

```text
AI-Meeting-Action-Tracker/
│
├── README.md
├── demo/
│   └── AI_Meeting_Action_Tracker_ServiceNow_Gemini_Demo.mp4
│
└── 0005973fc3460310972fb6ec0501314c/
```

---

## 🔮 Future Enhancements

- Speaker Identification
- Due Date Extraction
- Sentiment Analysis
- Email Notifications
- Microsoft Teams Integration
- Google Meet Integration

---

## 👨‍💻 Author

**S Addithya**

- GitHub: https://github.com/S-Addithya
- LinkedIn: https://www.linkedin.com/in/addithya-s-872383286/
