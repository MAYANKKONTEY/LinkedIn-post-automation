# Linkedin-mcp-agent
AI agent that writes LinkedIn posts in my voice with Claude, sends them to Telegram for approval, and publishes them through the official LinkedIn API on a daily GitHub Actions schedule.

# LinkedIn AI Agent 🤖

An agent that writes and publishes LinkedIn posts for me, but only after I approve them.

## How it works
1. **Generate** – Claude writes a post from my topic list, in my voice
2. **Review** – the draft goes to my Telegram with Approve / Reject buttons
3. **Publish** – approved posts go live through the official LinkedIn Posts API
4. **Schedule** – GitHub Actions runs it every morning

## Tech stack
Python · Claude API · LinkedIn Posts API (OAuth 2.0) · Telegram Bot API · GitHub Actions

## Why I built it
To post every day without spending an hour on each post. Nothing goes live without my approval.
