# n8n Daily News Digest 📰

A simple automation built with **n8n** that fetches the latest technology news and delivers it to a Discord channel.

## 🚀 How it Works
1.  **Trigger**: Every day at 8:00 AM, the workflow starts automatically.
2.  **Fetch**: It reads the official BBC Technology RSS feed to get the latest headlines.
3.  **Deliver**: It formats the news into a clean message and sends it to a Discord channel via a Webhook.

## 🛠️ Setup Instructions
To use this project yourself:
1.  Install [n8n](https://n8n.io/) locally or use the cloud version.
2.  Import the `workflow.json` file from this repository into your n8n canvas.
3.  Create a **Webhook** in your Discord Server settings.
4.  Open the "Discord Webhook" node in n8n and paste your Webhook URL into the URL field.
5.  Activate the workflow!

## 📦 Requirements
*   n8n (Local or Cloud)
*   Discord Server (with Webhook permissions)
*   Internet Connection

## 📜 License
MIT
