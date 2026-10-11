# Automated Meeting Scheduler (n8n Workflow)

An automated workflow built using **n8n** to streamline meeting scheduling and event creation using webhooks and REST APIs.

## 📌 Overview
This workflow automates meeting setup by capturing trigger events via webhooks, processing incoming JSON payloads, and interfacing with calendar APIs to automatically output meeting details.

## 🛠️ Features
- **Webhook Integration:** Receives real-time scheduling requests.
- **JSON Payload Processing:** Parses candidate/meeting parameters dynamically.
- **API Automation:** Connects with scheduling nodes to generate Google Meet events automatically.

## 🚀 How to Import and Run
1. Download the `n8n-meeting-scheduler.json` file from this repository.
2. Open your [n8n canvas](https://n8n.io/).
3. Click the top-right menu and select **Import from File**.
4. Upload `n8n-meeting-scheduler.json` and configure your API credentials.
5.
