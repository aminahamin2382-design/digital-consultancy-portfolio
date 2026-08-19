# AI Agents & Workflow Automations

This repository documents the logic, system prompts, and architectural designs of the AI agents and automated workflows I have built for digital consultancy and business scaling.

## 🤖 1. Custom AI Assistant: AILabBot
AILabBot is a specialized AI assistant designed to act as a frontline digital consultancy agent. It handles queries related to e-commerce storefront strategies, n8n node automation, and digital product design.

*   **Live Bot:** **[Chat with AILabBot on Poe](https://poe.com/AILabBot)**
*   **LLM Engine:** Claude-Opus-4.6 (Anthropic)

### 🧠 System Prompt (Logic & Constraints)
To ensure the bot acts purely as a B2B consultant, it is driven by the following core prompt engineering parameters:
> "You are an expert AI assistant representing an independent digital consultancy practice. Your primary domain includes e-commerce storefront strategies (Etsy, Shopify), n8n workflow automation, and digital product design. Keep your responses highly professional, direct, analytical, and focused on business scaling. Do not use generic buzzwords. If a user asks for complex technical deployments or hands-on implementation, politely instruct them to contact the consultant directly for a consultation."

## ⚙️ 2. Database & SEO Automation (n8n)
*Note: The actual JSON export of the n8n workflow can be found in this repository as `seo-automation-workflow.json`.*

### Architecture Overview
This workflow replaces 5 hours of manual SEO research and content formatting with a 10-minute automated pipeline.
*   **Data Ingestion:** Web scraping nodes (via Apify/HTTP requests) gather raw market data.
*   **Processing:** The data is fed into content-generation APIs for structuring and SEO optimization.
*   **Output:** The finalized content is automatically pushed to the CMS/database, maintaining strict formatting guidelines.

## 🚀 Skills Demonstrated
*   Advanced Prompt Engineering
*   API Integrations & Low-Code Development (n8n, GoHighLevel)
*   Business Process Automation (BPA)