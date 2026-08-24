# Gemini Voice Chatbot (Arabic Edition)

This is a simple, voice-activated AI chatbot powered by Google’s Gemini API. I built this project to create a seamless voice assistant experience directly in the browser, specifically tuned for Arabic (ar-SA) speech recognition and synthesis.

 this project uses PHP for the backend (g.php). Why? Because I wanted it to be easily deployable on free or cheap shared hosting providers (like InfinityFree) that don't support Node.js environments. 

 ## Features

-  **Speech-to-Text (STT):** Talk to the bot using your voice via the browser's Web Speech API.
-  **Text-to-Speech (TTS):** The bot reads the responses back to you out loud.
-  **Gemini AI:** Powered by gemini-3.6-flash for fast, low-latency, and smart responses.
-  **Sleek Dark UI:** Modern, mobile-friendly chat interface built with pure CSS (no heavy frameworks).
-  **Secure API Handling:** Your Gemini API key stays safe on the server-side, never exposed to the client.
-  **Shared-Hosting Friendly:** 100% PHP backend. If your host supports PHP, it runs.

## Tech Stack

- **Frontend:** JavaScript, HTML5, CSS3
- **Backend:** PHP (cURL)
- **APIs:** Google Gemini API, Web Speech API
- **Target Hosting:** InfinityFree, XAMPP, cPanel, or any standard LAMP stack.

## Getting Started

Want to run this locally or deploy it to your server? Follow these steps:

### 1. Get your Gemini API Key
Head over to [Google AI Studio](https://aistudio.google.com/app/apikey) and generate your free API key.

### 2. Configure the Backend
Open config.php and paste your API key:

define('GEMINI_API_KEY', 'YOUR_NEW_API_KEY_HERE');

