# n8n Railway Deployment (Free HTTPS)

This is a simple setup to deploy n8n on Railway for FREE with HTTPS and Telegram Trigger support.

## 🔧 Setup Instructions

1. **Create a GitHub Repo**
   - Push this folder to GitHub (e.g., `n8n-railway`)

2. **Deploy to Railway**
   - Go to https://railway.app
   - Click "New Project" → "Deploy from GitHub Repo"
   - Select your repo

3. **Set Environment Variable in Railway**
   - Go to "Variables" tab
   - Add: `WEBHOOK_URL = https://your-n8n.up.railway.app`
   - Click Restart Deployment

4. **Login to n8n**
   - Username: `admin`
   - Password: `strongpassword123`

Now n8n will run with HTTPS and your Telegram Trigger nodes will work!

---
