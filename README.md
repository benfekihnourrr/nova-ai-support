# 🤖 NOVA AI Support

## AI-Powered Customer Support Web App

NOVA AI Support is a customer support web application designed to help support teams manage conversations, generate AI-assisted responses, summarize customer issues, organize knowledge, and escalate conversations to human agents.

The project combines a modern support dashboard with AI-focused features and an optional server-side OpenAI API integration.

## 🌐 Live Demo

https://tubular-clafoutis-5fa406.netlify.app/

## ✨ Features

### 💬 Support Inbox

- Manage multiple customer conversations
- View customer information
- Review conversation history
- Organize support requests
- Track conversation status
- Resolve customer issues

### 🤖 AI Assistance

- AI reply suggestions
- Conversation summaries
- Suggested support responses
- AI-assisted customer service workflow
- Configurable AI settings

### 👤 Human Escalation

Support conversations can be escalated from AI-assisted support to a human agent when additional assistance is required.

This demonstrates how AI can support customer service teams rather than replacing the human support workflow.

### 📚 Knowledge Base

- Manage support FAQs
- Store common questions and answers
- Maintain reusable support information
- Provide context for support workflows

### 📊 Analytics Dashboard

The analytics section provides an overview of customer support activity and performance.

### ⚙️ AI Settings

The application includes configurable AI settings for demonstrating how AI behavior could be managed within a customer support platform.

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript
- Node.js
- OpenAI API integration example
- Local Storage
- Responsive Web Design
- UI/UX Design

## 🧠 AI Architecture

The project includes an optional Node.js server example for connecting the application to the OpenAI API.

The API key is handled through a server-side environment variable:

    OPENAI_API_KEY

API keys should never be stored directly inside client-side JavaScript or committed to a public GitHub repository.

## 💾 Data Storage

The demonstration version uses browser Local Storage for application data such as knowledge-base information and interface state.

A production version could replace this with a secure backend and database.

## 🎯 Project Purpose

This project demonstrates how AI can be integrated into a customer support workflow.

It showcases:

- AI-assisted response generation
- Conversation summarization
- Customer support management
- Human escalation workflows
- Knowledge-base management
- Analytics dashboards
- Front-end development
- Server-side AI integration concepts

## 📸 Screenshots

### Support Inbox & AI Assistant

![NOVA AI Support Inbox](nova-ai-support-inbox.png)

### Analytics Dashboard

![NOVA AI Support Analytics](nova-ai-support-analytics.png)

### Knowledge Base

![NOVA AI Support Knowledge Base](nova-ai-support-knowledge-base.png)

### AI Settings

![NOVA AI Support Settings](nova-ai-support-settings.png)

## 📂 Project Structure

    nova-ai-support/
    ├── index.html
    ├── style.css
    ├── app.js
    ├── server.js
    ├── README.md
    ├── nova-ai-support-inbox.png
    ├── nova-ai-support-analytics.png
    ├── nova-ai-support-knowledge-base.png
    └── nova-ai-support-settings.png

## ⚠️ Demo Notice

The deployed application is a demonstration of the customer support interface and workflow.

AI functionality in the front-end demo may use simulated responses. The project includes an optional server-side implementation for connecting to a real AI API.

For production use, additional authentication, database storage, security controls, rate limiting, and server-side knowledge retrieval would be required.

## 👨‍💻 Developer

Developed by **Nour Ben Fekih Ahmed**

Software Engineering Student | Web Development | Automation | AI-Assisted Development
