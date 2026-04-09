# 🚀 n8n News & Automation Collection

A collection of specialized n8n workflows for automated news aggregation, security monitoring, and personal productivity.

---

## 🛡️ Featured: Cyber-Watch ⚠️
The **Cyber-Watch** workflow is a robust news aggregator designed to keep you updated on the latest in Cybersecurity, Hardware, and Tech-News.

### 🛠️ How it works
1. **Source:** Fetches data via RSS Feeds from multiple tech news platforms.
2. **Filtering:** Uses a `Switch Node` to categorize incoming news into specific topics (e.g., Security, Hardware, Software).
3. **Delivery:** Formats the data into a clean, readable layout and sends it directly to a **Discord** channel via Webhook.

### ⚙️ Setup
* **Credentials:** You will need to set up your own Discord Webhook credentials within n8n.
* **Customization:** Easily add your own RSS sources in the initial `RSS Read` node.

---

## 📅 Personal Notifications (German)
I also included my personal calendar notification workflow. 

* **Note:** This specific workflow is kept in **German**, as it features custom, personality-driven greetings for special events like:
    * Sysadmin Day 💻
    * Pride Month 🏳️‍🌈
    * Christmas & New Year 🎄

---

## 📖 How to use these workflows
1. Download the `.json` file of the workflow you want.
2. In your n8n instance, click on **"Import from File"**.
3. Set up your own API keys/Credentials for the respective services (Discord, Google, etc.).
4. Hit **"Execute"** and enjoy!

---
*Created with ❤️ by afischer587-creator*
