# Ticketing Chatbot On Whatsapp

A full-stack, multilingual WhatsApp chatbot built to streamline the event and ticketing process. Designed to provide end-to-end customer interaction, real-time event updates, and AI-powered support via conversational automation. This project simulates real-world enterprise use cases with a focus on clean architecture, scalable backend design, and cross-functional development patterns.
## Features ✨

- **Multilingual Support**: Available in both English and Hindi for a wider audience.
- **Ticket Booking**: Helps users book tickets for museum visits by selecting the number of adults and children.
- **Exhibitions and Events**: Provides updates about current and upcoming exhibitions and events.
- **AI-Based Customer Support**: Powered by Google Generative AI, the chatbot offers 24/7 support and answers to visitor queries.
- **Secure Payment Integration**: Integration with payment gateways (like RazorPay) to facilitate smooth transactions (optional future feature).

## System Flow 🚀

1. **Visitor Selection**: Users are asked about the number of adults and children visiting. The chatbot stores the responses and confirms the visitor count.
2. **Event & Exhibitions Updates**: The chatbot provides up-to-date information about ongoing or upcoming events and exhibitions.
3. **Customer Support**: Users can ask any questions, and the chatbot responds using AI from Google Generative API. The chatbot also handles requests to exit the conversation loop.
4. **Multilingual Responses**: The system is capable of responding in both English and Hindi, based on the user's selected language.

## System Flow Diagram 🖼️

Here’s a high-level overview of the system flow for the WhatsApp Chatbot-Based Ticketing System:

![System Flow](https://github.com/bpranav83/Whatsapp-Chatbot-Based-Ticketing-System/blob/main/scripts/opns-Page-4.drawio.png)

## Tech Stack 🛠️

- **Backend**: 
  - Node.js
  - Python
- **Database**:
  - MongoDB (for storing user state and ticketing information)
- **API Services**: 
  - Google Generative AI (Gemini API) for AI-based responses
  - WppConnect (WhatsApp messaging framework)
- **Environment Variables**: 
  - `GOOGLE_API_KEY`: Used for connecting with Google Generative AI

## Installation 📦

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/whatsapp-chatbot-ticketing-system.git
2. Install the necessary dependencies:
   ```bash
   npm install
3. Set up environment variables by creating a .env file in the root directory:
     ```bash
   GOOGLE_API_KEY=your_google_api_key_here
4. Start the chatbot:
  ```bash
   npm start
```
## Highlights for Employers (Booking Holdings Perspective)
- Demonstrates strong full-stack skills, REST API usage, and messaging integration.

- Reflects core interests in software engineering, platform-based tools, and enterprise logic flows.

- Shows real-world use of AI for scalable customer engagement.

- Developed in an agile mindset with focus on modularity, maintainability, and user-centric design.


