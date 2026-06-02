# Avilax AutoCita v1

WhatsApp/Telegram appointment booking bot for Venezuelan beauty salons.

## Stack
- n8n (workflow automation)
- Telegram Bot API
- Google Sheets (appointment storage)
- Google Calendar (event creation)
- OpenAI GPT-4o mini (AI agent)

## Architecture
Telegram/WhatsApp → n8n AI Agent → Google Sheets + Calendar → Response to client

## Setup
1. Import `workflows/` JSON into n8n
2. Configure credentials (Telegram, Google, OpenAI)
3. Set webhook URL
4. Publish workflow

## Status
MVP in development — Telegram functional, WhatsApp (Evolution API) pending.
