# 🏢 AI-Powered Real Estate Research Assistant (n8n Workflow)

[![n8n.io](https://img.shields.io/badge/n8n-Workflow-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)
[![Google Gemini](https://img.shields.io/badge/Google_Gemini-3.1_Flash_Lite-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![Tavily API](https://img.shields.io/badge/Tavily-Search_%26_Extract-000000?style=for-the-badge)](https://tavily.com/)
[![Gmail Integration](https://img.shields.io/badge/Gmail-Automated_Reporting-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/)

An autonomous, end-to-end real estate market research workflow built using **n8n**. This AI Agent automatically parses property URLs (e.g., StreetEasy, Zillow) or location prompts, performs web extraction with automatic search fallbacks, calculates financial metrics (rental yields, carrying costs, ROI), and delivers clean HTML investment reports straight to Gmail.

---

## 🌟 Key Features

* **💬 Natural Language & URL Trigger**: Accepts general market queries or direct property listing URLs via chat.
* **🧠 Autonomous AI Brain**: Powered by `Google Gemini 3.1 Flash Lite` acting as a Senior Real Estate Analyst.
* **🌐 Web Scraping & Extraction**: Utilizes **Tavily Extract API** to fetch raw listing data directly.
* **🛡️ Smart Fallback Execution**: Automatically switches to **Tavily Search API** if live web scraping encounters anti-bot protections (Cloudflare / PerimeterX 403 Forbidden errors).
* **✉️ Direct HTML Email Delivery**: Generates structured HTML code directly from the LLM and delivers formatted reports via **Gmail** without needing extra conversion nodes.

---

## 🛠️ Architecture & Workflow

![Workflow Screenshot](https://i.ibb.co.com/3ysZvfzN/Screenshot-2026-08-09-084451.png) 

             ▼           ▼     
===
