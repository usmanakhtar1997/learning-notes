# Learning log: week 1

Date: 15-Oct-2026

## Why this log exists
I build SaigeSDR with AI tools. This log tracks what I'm learning so I can review and understand the code behind it.

## What I learned
- **API:** a way for one app to ask another app to do something. SaigeSDR uses APIs for phone calls (Twilio, Telnyx), transcription (Deepgram), AI (OpenAI, Anthropic, Google) and email (Gmail).
- **OAuth:** lets a user connect their Gmail without sharing their password. The app asks for specific permissions called scopes.
- **Webhook:** another service calling my app when something happens, for example a reply arriving or a call ending.
- **Row Level Security:** database rules that make sure a user only sees their own organization's data.
- **Migration:** moving SaigeMock off Lovable meant cloning the code from GitHub and deploying it on Vercel with my own Supabase database.
