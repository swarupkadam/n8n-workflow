# ⚡ n8n Workflows on Easy Mode
Build Automations with Cursor + Claude Code

You've probably seen people building full automation systems in minutes — lead generation pipelines, onboarding systems, invoice automation — while others are still manually connecting nodes in n8n.

Good news :
You don't need to learn n8n the hard way.

Using Cursor + Claude Code + n8n, you can describe workflows in plain English and let AI build them automatically.

This guide helps you set everything up in under 10 minutes.

## 🚀 What You're Setting Up

| Tool | Purpose |
|------|---------|
| Cursor | AI-powered code editor |
| Claude Code | AI assistant inside Cursor |
| n8n | Automation workflow platform |
| MCP (Model Context Protocol) | Connects AI directly to n8n |

Once connected, Claude Code can:

✅ Create workflows  
✅ Edit automations  
✅ Connect integrations  
✅ Deploy workflows directly into n8n

No manual node wiring required.

## ✅ Requirements

- Computer (Windows / Mac / Linux)
- Internet connection
- Free n8n account
- ~10 minutes setup time
- No coding experience required

## 🛠 Step-by-Step Setup

### 1️⃣ Install Cursor

- Visit https://cursor.com
- Download for your OS
- Install like a normal application

💡 Cursor is free and includes built-in AI features.

### 2️⃣ Install Claude Code Extension

Inside Cursor:

- Open Extensions panel (4-square icon)
- Search for: `Claude Code`
- Install the official extension
- Wait for the Claude icon to appear

🧠 Claude Code allows you to chat with AI that can read and execute project code.

### 3️⃣ Create Your n8n Account

- Go to https://n8n.io
- Create a free account
- Open dashboard
- Navigate: `Profile → Settings → API`
- Click **Create API Key**
- Copy and save the key securely

⚠️ Never upload your API key to GitHub.

### 4️⃣ Clone the n8n MCP Repository

This repository connects Claude Code with n8n.

Open Cursor terminal:

- `Ctrl + \`` (or `Cmd + \`` on Mac)

Run:

```bash
git clone <n8n-mcp-repository-url>
```

Then open the folder:

- `File → Open Folder`

📁 This acts as the translator between Claude and n8n.

### 5️⃣ Connect n8n to Claude Code

- Open Claude Code panel
- Paste your n8n API key
- Or add it inside `.env`

Example:

```env
N8N_API_KEY=your_api_key_here
```

✅ Connection success = confirmation message or green checkmark.

### 6️⃣ Build Your First Workflow

Now simply describe what you want.

#### Example: Lead Generation Workflow
Build an n8n workflow that:
1. Triggers when a new Google Sheet row is added
2. Enriches company data
3. Sends welcome email via Gmail
4. Notifies Slack channel

#### Example: Client Onboarding
Build an n8n workflow that:
1. Triggers from webhook
2. Creates Google Drive folder
3. Sends onboarding email
4. Creates project task
5. Sends Slack notification

#### Example: Invoice Automation
Build an n8n workflow that:
1. Runs monthly
2. Reads client data from Google Sheets
3. Generates invoices
4. Emails invoices
5. Logs results back to sheet

Claude Code will:

✅ Plan workflow  
✅ Create nodes  
✅ Connect integrations  
✅ Deploy inside n8n

### 7️⃣ Verify & Activate Workflow

Inside n8n:

- Open dashboard
- Select workflow
- Review nodes
- Click **Test Workflow**
- Toggle **Active**

🎯 Always test using dummy data first.

## 🎉 Setup Complete

You just:

✅ Installed Cursor  
✅ Added Claude Code  
✅ Created n8n API access  
✅ Connected MCP server  
✅ Built AI-generated workflows  
✅ Activated automation

You skipped months of manual learning.

## ⚡ Quick Reference

| Action | Method |
|--------|--------|
| Open Claude | Sidebar Claude icon |
| Open Terminal | `Ctrl + \`` |
| Clone Repo | `git clone <url>` |
| Test Workflow | Test Workflow button |
| Activate Workflow | Toggle Active |
| Create Workflow | Describe in chat |

## ❓ Common Questions

### Do I need coding knowledge?
No. Describe workflows in plain English.

### Is Cursor free?
Yes. Paid plans increase usage limits.

### Is n8n free?
Yes — free cloud tier or fully free self-hosted version.

### What is MCP?
Model Context Protocol — allows AI tools to control external platforms.

### Workflow not working?
Ask Claude Code to debug or check Execution Logs in n8n.

### Can I sell these workflows?
Yes. Automation services are highly valuable for businesses.

## 💡 Workflow Ideas

- Lead generation automation
- Client onboarding system
- Monthly invoice automation
- Social media monitoring
- Automated email follow-ups
- Data synchronization
- Meeting preparation automation
- Automated reporting dashboards

## 📈 What's Next?

- Chain workflows together
- Add retry & error handling
- Sell automation services
- Self-host n8n for unlimited workflows

## 🔗 Resources

- Cursor Download
- n8n Official Website
- n8n Documentation
- Claude Code Docs
- MCP Overview

## 📄 Source

Source adapted from setup guide:  
**n8n Workflows on Easy Mode: Build Automations With Cursor + Claude Code**
