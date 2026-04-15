# ask-vendor-management
This repository hosts the GUI and API interaction code where AskVM is a chatbot taking questions from Vendor Managers, connecting to Ask AT&amp;T LLMs via Ask AT&amp;T API and provides answers back after searching Vendor Management documents.

# Ask Vendor Management Chatbot (minimal)

Overview:
- Simple Express backend + static frontend.
- Backend performs OAuth2 client_credentials using `CLIENT_ID`/`CLIENT_SECRET`, then calls `API_URL`.
- Frontend provides a minimal chat UI and posts questions to `/api/ask`.

Setup:
1. Copy `.env.example` to `.env` and fill in `CLIENT_ID`, `CLIENT_SECRET`, `AUTH_URL`, and `API_URL`.
2. Install and run:

```bash
npm install
npm start
