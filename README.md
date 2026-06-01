# MCP Server Personal Assistant

A Model Context Protocol (MCP) server that connects AI models to 
external tools — enabling a fully autonomous personal assistant 
via Telegram. One message handles everything.

## Demo

[

![Watch the demo](https://img.youtube.com/vi/ppyr-vR8kqU/0.jpg)

](https://www.youtube.com/watch?v=ppyr-vR8kqU)

## How It Works

1. Telegram Trigger receives the user message
2. AI Agent processes the request and selects the appropriate tool
3. Response is sent back to the user via Telegram instantly

## What It Handles

- Google Calendar — create, update, and delete events
- Google Sheets — automatic event logging and summaries
- Gmail — read and compose emails
- Google Tasks — manage and track task list
- Notion — update and organize workspace
- Context7 MCP — fetch live technical documentation

## Tools Used

- n8n
- Telegram
- OpenAI Chat Model
- Google Calendar, Sheets, Gmail, Tasks
- Notion
- Context7 MCP
