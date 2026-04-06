# 💬 AI LinkedIn First Message Automation (n8n Workflow)

## 📌 Overview

This project is an **AI-powered LinkedIn outreach automation system** that generates personalized first messages for leads using n8n and OpenAI.

It automates:
👉 Lead data processing → AI message generation → Email notification → Data tracking

---

## ⚙️ Key Features

### 📊 1. Lead Data Input

* Reads lead data from Google Sheets
* Includes:

  * Name
  * LinkedIn Profile URL
  * Business Information
  * Product/Service

---

### 🧠 2. AI Message Generation

* Uses OpenAI (GPT-4.1-mini)
* Generates:

  * Short, natural LinkedIn openers
  * Human-like conversation starters
* Follows strict rules:

  * 2–3 sentences
  * No selling tone
  * One soft question at the end

---

### 🎯 3. Personalization Engine

* Tailors messages based on:

  * Lead profile
  * Business context
  * Product relevance
* Ensures high engagement potential

---

### 📧 4. Automated Notification

* Sends generated message via Gmail
* Includes:

  * Lead details
  * Suggested first message

---

### 📈 5. Output Tracking

* Stores generated messages in Google Sheets
* Updates:

  * Message content
  * Status
* Enables tracking and reuse

---

## 🛠️ Tech Stack

* **n8n** (Workflow Automation)
* **OpenAI API (GPT-4.1-mini)**
* **Google Sheets API**
* **Gmail API**
* **JavaScript (n8n Code Nodes)**

---

## 📂 Project Structure

* `workflow.json` → Main automation workflow

---

## 🚀 How to Use

1. Import `workflow.json` into n8n
2. Connect:

   * OpenAI API
   * Google Sheets
   * Gmail
3. Add lead data in Google Sheets
4. Run the workflow
5. Receive:

   * AI-generated LinkedIn message
   * Email notification
   * Updated tracking sheet

---

## 💡 Use Cases

* LinkedIn outreach automation
* Sales prospecting
* Lead engagement systems
* Cold messaging optimization

---

## 🔥 Highlights

* Human-like AI messaging
* Fully automated workflow
* Personalized outreach at scale
* Clean and structured data pipeline

---

## 👤 Author

**Tarun Patel**
