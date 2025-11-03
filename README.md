🤖 CyberTarr-A's n8n Workflow Collection

Welcome to my repository of custom n8n.io workflows! 👋 This collection showcases various automation tasks, from AI-powered content generation and lead scoring to comprehensive data scraping and monitoring.

📜 Table of Contents

🤖 AI & Language Workflows

👽 Reddit Automation & Scraping

🪙 Crypto & Web Scraping

🚀 How to Use

👋 About Me

🤖 AI & Language Workflows

1. 🧠 AI Content Strategy Generator (Gemini)

➡️ View Workflow File

This workflow automates the creation of content strategy reports by analyzing social media trends. It scrapes Reddit, YouTube, and X (Twitter) for a given keyword, then uses a multi-stage Google Gemini AI pipeline to filter, perform deep analysis, and synthesize a final HTML report.

Key Services: n8n, Google Gemini AI, Reddit API, YouTube API, Twitter API, Gmail, Google Sheets.

2. 📸 AI Image Captioning (RAG)

➡️ View Workflow File

Provides an API endpoint for generating image captions using a Retrieval-Augmented Generation (RAG) agent. It uses an Anthropic (Claude) model, OpenAI embeddings, and a Weaviate vector store to provide context-aware captions.

Key Services: n8n, Anthropic Claude, OpenAI (Embeddings), LangChain, Weaviate (Vector Store), Slack.

👽 Reddit Automation & Scraping

3. 🎯 Reddit Lead Generator

➡️ View Workflow File

A sophisticated workflow to automatically find, qualify, and respond to potential leads on Reddit. It searches posts, checks competitor mentions, uses a multi-stage AI process to qualify intent, and generates personalized responses.

Key Services: n8n, Reddit API, AI/LLM (via HTTP), CRM (via HTTP), ML Model (via HTTP).

4. 🗄️ Reddit Post Fetcher (Postgres)

➡️ View Workflow File

A high-frequency (2-minute) workflow that fetches new posts from a list of subreddits and stores them in a PostgreSQL database. It uses the database to manage state (last post ID) and updates engagement stats (upvotes, comments) on conflict.

Key Services: n8n, Reddit API, PostgreSQL.

5. 🔎 Reddit Post & Comment Extractor

➡️ View Workflow File

A webhook-triggered workflow that scrapes Reddit for posts (and their top comments) based on keywords. It filters the results by date and upvotes, then formats the output into a clean Markdown report.

Key Services: n8n, Reddit API.

🪙 Crypto & Web Scraping

6. 💸 Airdrop + Faucet + NFT Radar v3

➡️ View Workflow File

A comprehensive crypto monitoring tool. It scrapes numerous sources—including APIs (CoinMarketCap, Zora, OpenSea, Galxe, Zealy) and websites (Airdrops.io)—to find new airdrops, faucets, and NFT drops. New items are de-duplicated, logged to Google Sheets, and sent as Telegram notifications.

Key Services: n8n, Google Sheets, Telegram, Web Scraping, multiple Crypto APIs.

7. 🕸️ Airdrops.io Full Scraper

➡️ View Workflow File

A scheduled web scraper that fetches the sitemap from Airdrops.io, parses all project URLs, then loops through each URL to scrape the airdrop's title, description, and claim link using Regex.

Key Services: n8n, Web Scraping (HTTP), Regex.

🚀 How to Use

Download: Click one of the "View Workflow File" links, then right-click and "Save As..." to download the .json file.

Import to n8n: Open your n8n canvas, click "Import," and either "Import from URL" (by pasting the GitHub raw link) or "Upload" the downloaded file.

Configure Credentials: Most workflows require API keys or other credentials. Open the nodes (especially "Secrets" nodes or nodes with a key icon 🔑) and add your own credentials.

Activate: Once configured, toggle the "Active" switch in the top-right corner.

👋 About Me

I'm Jashraj Shah (CyberTarr-A), an AI Developer and Researcher specializing in machine learning, automation, and web scraping.

🐙 GitHub Profile: github.com/cybertarr-A

🌐 Main Portfolio: cybertarr-a.github.io/cybertarr-portfolio/
