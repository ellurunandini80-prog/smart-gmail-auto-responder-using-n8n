# Smart Gmail Auto-Responder using n8n

## Project Overview
This project is a smart Gmail auto-responder built using n8n automation.  
It automatically reads incoming emails, identifies the email purpose based on the subject, sends appropriate replies, and applies Gmail labels such as Support, Contact, or Career.

## Features
- Automatically triggers on new Gmail messages
- Classifies emails using conditions and switch logic
- Sends predefined replies for:
  - Support emails
  - Contact inquiries
  - Career-related emails
- Adds Gmail labels for better inbox organization
- Fully automated workflow using n8n

## Workflow Steps
1. Gmail Trigger detects a new incoming email
2. IF node checks email conditions
3. Switch node routes emails based on subject
4. Gmail Reply node sends auto-responses
5. Gmail Label node categorizes emails

## Tools & Technologies
- n8n (Workflow Automation)
- Gmail Trigger & Gmail Nodes
- Conditional Logic (IF & Switch)
- JSON Workflow Export

## Files
- Smart Gmail Auto-Responder using n8n.json — n8n workflow file

## Use Case
Useful for professionals or businesses to automatically manage incoming emails, reduce response time, and keep Gmail inbox organized.

## How to Use
1. Import the JSON file into n8n
2. Connect your Gmail account
3. Activate the workflow
4. Incoming emails will be handled automatically
