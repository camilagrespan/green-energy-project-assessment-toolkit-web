# Deploy to Vercel - Step by Step

## What You'll Get
- Live URL: `https://your-project-name.vercel.app`
- Automatically updated when you push changes
- Free hosting (no credit card required)
- HTTPS by default

---

## Steps to Deploy (5 minutes)

### Step 1: Create a GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it: `green-energy-toolkit` (or your choice)
3. Click **Create repository**
4. Copy the commands shown on the next page

### Step 2: Push Your Toolkit Files to GitHub
In your terminal, run these commands in the toolkit folder:

```bash
git init
git add .
git commit -m "Initial commit: Green Energy Project Assessment Toolkit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/green-energy-toolkit.git
git push -u origin main
```

(Replace YOUR-USERNAME with your actual GitHub username)

### Step 3: Deploy to Vercel
1. Go to [vercel.com](https://vercel.com)
2. Click **Sign Up** (use GitHub for fastest setup)
3. Click **Import Project**
4. Select your `green-energy-toolkit` repository
5. Click **Import**
6. Vercel will auto-detect settings (no changes needed)
7. Click **Deploy**

**Done!** Your live URL will appear in 1-2 minutes.

---

## After Deployment

### Your Live Toolkit
- **View it:** Visit the URL (e.g., `https://green-energy-toolkit.vercel.app`)
- **Share it:** Send the URL to anyone who needs the toolkit
- **Update it:** Any changes you push to GitHub automatically redeploy

### Files Deployed
- ✅ `Green Energy Project Assessment Toolkit.html` — Main toolkit
- ✅ `vercel.json` — Configuration (already set up)
- ✅ All resources and styling included

---

## Troubleshooting

**Q: Where's my live URL?**
A: Go to [vercel.com/dashboard](https://vercel.com/dashboard), click your project, and find the domain link.

**Q: Can I use a custom domain?**
A: Yes! Go to Project Settings → Domains in Vercel and add your domain.

**Q: How do I update the toolkit?**
A: Edit your HTML file locally, commit to GitHub, and push. Vercel redeploys automatically in ~1 minute.

**Q: Is the toolkit password protected?**
A: No, but you can add authentication through Vercel if needed.

---

## Support
- Vercel docs: [vercel.com/docs](https://vercel.com/docs)
- GitHub guides: [github.com/skills](https://github.com/skills)
