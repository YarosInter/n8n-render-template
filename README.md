# n8n Client Template for Render

This repo allows you to deploy one isolated n8n instance per client using Render.

## 🔧 How to Deploy a Client

1. Go to https://render.com and log in
2. Click "New +" → Web Service
3. Connect to this GitHub repo
4. Render auto-detects `render.yaml`
5. Set environment variables from `.env.example`
6. Click **Deploy**

Each deployment includes its own PostgreSQL DB and auth.

## 🔁 To Deploy for More Clients

Repeat the process:
- Use same repo
- Give each service a unique name (e.g., client2-n8n)
- Use different login credentials
