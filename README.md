# AI Customer Email Review Automation (n8n)

This project demonstrates an automated workflow that reads customer emails, detects product reviews, performs sentiment analysis using AI, and automatically generates a professional reply.

## Features

- Detects incoming emails using Gmail Trigger
- Extracts customer details and email content
- Uses AI to determine if the email is a product review
- Performs sentiment analysis (Positive / Negative / Neutral)
- Automatically generates a reply
- Logs review data into Google Sheets

## Tech Stack

- n8n
- AI (LLM)
- Gmail API
- Google Sheets
- JavaScript

## Workflow Overview

1. Gmail Trigger detects new email
2. Function node extracts email information
3. AI node analyzes review and sentiment
4. Workflow logs data to Google Sheets
5. Automated reply is sent to the customer

## Demo

See LinkedIn post for the full demo.

## How to Use

1. Import the workflow JSON file into n8n
2. Connect Gmail and Google Sheets credentials
3. Activate the workflow
