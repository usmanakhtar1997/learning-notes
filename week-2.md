# Learning Week 2
Date: 15-Oct-2026

## 4-line architecture
- **Front-end**
  - React + Tailwind and WebRTC for calling

This is used to show how the app looks for the user and how they can use it

- **Back-end**
  - Edge Functions / Serverless Functions or Cron Jobs

They are serverless functions that run when the user calls them from the front end and they close when their job is done. Also, cron jobs are scheduled jobs that run at a scheduled time and close when their work is done

- **Database**
  - PostgreSQL
  - RLS
  - Secrets Encrypted in Database
  - Supabase

PostgreSQL is the database software with 195 tables and each table has RLS (Row Level Security) added so it can check whether the user has permission to view the data in the table or not

- **Outside Service / 3rd Party**
  - Twilio/Telnyx
  - Deepgram
  - AI APIs
  - Retell

These are the 3rd-party applications we use to run our apps
