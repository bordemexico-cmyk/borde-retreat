# BORDÉ Oaxaca Retreat Website

## Deployment Instructions for Vercel

### Step 1: Prepare Files
✅ Already done - all files are ready!

### Step 2: Create Vercel Account
1. Go to https://vercel.com
2. Click "Sign Up"
3. Use your email: borde.mexico@gmail.com
4. Confirm email

### Step 3: Deploy to Vercel

**OPTION A: Upload Files (Easiest)**
1. Go to https://vercel.com/new
2. Click "Import Project"
3. Select "Other" or "From Git" → Choose folder upload
4. Upload the `borde-retreat` folder
5. Click "Deploy"
6. **Done!** You'll get a URL like: `https://borde-retreat-xxxxx.vercel.app`

**OPTION B: Using Git/GitHub**
1. Push this folder to GitHub
2. Go to https://vercel.com/new
3. Connect GitHub
4. Select your repo
5. Click "Deploy"

### Step 4: Add Custom Domain (Optional)
1. Once deployed, go to your project settings
2. Click "Domains"
3. Add your domain (e.g., borderetreat.com)
4. Follow DNS setup instructions

---

## File Structure

```
borde-retreat/
├── index.html          (Main website)
├── package.json        (Project info)
├── vercel.json         (Vercel config)
└── README.md           (This file)
```

---

## After Deployment

### Edit Content
1. Edit `index.html` in any text editor
2. Make changes
3. Re-upload to Vercel (or push to GitHub)

### Add Photos
Photos are currently from Google Drive URLs. To use local images:
1. Create an `images/` folder
2. Add your photos
3. Update image URLs in index.html from:
   ```html
   <img src="https://drive.google.com/uc?id=..." alt="...">
   ```
   To:
   ```html
   <img src="/images/photo-name.jpg" alt="...">
   ```

### Update Content
Find and replace in index.html:
- **WhatsApp:** Replace `https://wa.me/YOURWHATSAPP` with your WhatsApp link
- **Dates, Price, etc:** Update directly in the HTML
- **Text:** Edit any paragraph or section

---

## Support
Need help? Contact: borde.mexico@gmail.com
