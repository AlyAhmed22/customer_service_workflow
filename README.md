📖 Customer Service Automation for Restaurant (n8n Project)
🔎 Overview

This project is an AI-powered customer service workflow for a restaurant, built using n8n.
It allows customers to interact with the restaurant through Telegram, where an AI Agent can answer questions, manage orders, and update customer requests automatically.

❗ Problem

Restaurants usually spend a lot of time replying to customer inquiries and managing orders manually.
This leads to:

Delayed responses ⏱

Higher workload on staff 👩‍🍳

Errors in order management ❌

💡 Solution

Using n8n + AI Agent, I built a workflow that:

Connects Telegram to receive customer messages.

Uses an AI Agent (LLM) to understand and reply to customer queries.

Answers questions from a knowledge base (restaurant menu, policies, FAQs).

Automatically manages orders in Google Sheets (append, update, retrieve rows).

Keeps track of conversations using memory for a natural chat flow.

🛠 Tech Stack

n8n (workflow automation)

Telegram Bot API

Google Sheets (for order management & customer database)

Cohere Embeddings (for semantic search in knowledge base)

Supabase Vector Store (to store and query restaurant data)

LLM Chain + AI Agent (to process natural language queries)

🔄 Workflow Steps

Telegram Trigger – Captures incoming customer messages.

LLM Chain + Output Parser – Processes customer text and routes it to the correct prompt.

System Prompts – Specialized prompts for:

General questions (working hours, location, menu, etc.)

Order requests (place, update, or cancel an order)

FAQs from restaurant knowledge base

AI Agent + Memory – Generates human-like responses while remembering conversation context.

Google Sheets Integration – Orders are stored, updated, or retrieved directly in a Google Sheet.

Final Response – The bot replies instantly on Telegram with accurate information or order confirmation.

✅ Results

Customers get instant replies via Telegram.

Restaurant staff spend less time answering repetitive questions.

Orders are managed automatically and stored safely in Google Sheets.

AI-powered knowledge base ensures customers always get the right information.

🚀 Use Cases

Restaurants & Cafés

Small businesses needing AI-powered support

Any business that wants to connect Telegram + AI + Google Sheets
