# n8n Daily News Automation

An automated daily news email workflow built using n8n, Docker, Gmail OAuth, and News API.

## Features

- Automatically fetches latest news articles
- Runs every day at 6:00 AM
- Sends formatted emails through Gmail
- Uses JavaScript for article formatting
- Self-hosted using Docker
- Fully automated workflow

## Workflow Architecture

Schedule Trigger → HTTP Request → Split Out → Limit → JavaScript → Gmail Send Message

## Technologies Used

- n8n
- Docker
- Gmail OAuth2
- News API
- JavaScript

## Automation Flow

1. Schedule Trigger runs daily at 6 AM
2. News API fetches latest articles
3. Split Out processes multiple news items
4. Limit node filters required articles
5. JavaScript formats email content
6. Gmail node sends email automatically

## Setup

1. Install Docker
2. Run n8n container
3. Configure Gmail OAuth
4. Add News API key
5. Import workflow JSON
6. Publish workflow

## Author

Jaswanth
