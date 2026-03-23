# Voice Agent Call Automation

An open-source platform for building and deploying real-time, low-latency AI voice agents for call automation. This project explores the technical architecture required for AI-driven phone agents that can handle dynamic conversations and convert leads.

## Key Features
* Real-time, low-latency voice interaction pipeline.
* AI agent capable of dynamic conversation and lead conversion logic.
* Scalable deployment setup for handling concurrent calls.

## Tech Stack
* Python
* FastAPI
* WebRTC / Twilio (Voice APIs)
* LLM Integration (e.g., OpenAI, Anthropic)

## Getting Started
1. Clone the repository: `git clone https://github.com/zoreanuj/voice-agent-call-automation.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set your environment variables (API keys).
4. Run the server: `uvicorn main:app --reload`