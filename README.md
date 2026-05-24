# AI News Automation Bot using n8n

An AI-powered automation workflow built using n8n that fetches news from RSS feeds, summarizes articles using Gemini AI, and sends automated summaries directly to Telegram.

## Features

* Automated scheduled workflow
* RSS feed news collection
* AI-generated summaries using Gemini
* Telegram bot integration
* Structured news delivery
* Workflow automation using n8n

## Workflow Architecture

Schedule Trigger
→ RSS Feed Collection
→ AI Summarization
→ Telegram Delivery

## Technologies Used

* n8n
* Gemini API
* Telegram Bot API
* RSS Feeds

## Workflow Nodes

1. Schedule Trigger
2. Edit Fields
3. Split Out
4. RSS Read
5. Sort
6. Limit
7. Basic LLM Chain
8. Telegram Node

## How It Works

1. The workflow starts automatically using a schedule trigger.
2. RSS feeds are fetched from news websites.
3. Articles are processed and limited.
4. Gemini AI summarizes the news.
5. Summaries are sent to Telegram automatically.

## Future Improvements

* Combined news digest
* Multiple news categories
* Database integration
* Duplicate news filtering
* Web dashboard
* Email notifications

## Project Demo

## Demo Video
https://www.linkedin.com/feed/update/urn:li:activity:7464245515132506112/?originTrackingId=6Z5xLQrJRVuXl8eBxfXsNg%3D%3D

## Workflow Screenshot
<img width="1786" height="780" alt="Screenshot 2026-05-24 143301" src="https://github.com/user-attachments/assets/f8976cdc-56c2-4284-9cdf-9c0915d41ca6" />


## Learning Outcomes

* Workflow automation
* API integration
* AI prompt engineering
* Telegram bot integration
* RSS parsing
* AI-powered backend workflows
