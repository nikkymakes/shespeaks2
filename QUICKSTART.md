# She Speaks - Quick Start Guide

**Created by: Adenike Omoregbee**

---

## 🎯 What You're Looking For:

### "I just want to see it work NOW"
→ **Open `she-speaks-demo.html`**  
Complete sample interpretation, no setup required!

---

### "I want to deploy the full app"
→ **Follow Netlify deployment** (5-10 minutes)

**Quick Steps:**
1. Get API key: console.anthropic.com (free)
2. Push files to GitHub
3. Deploy on Netlify: app.netlify.com
4. Add API key as environment variable
5. Done!

**Detailed guide in README.md**

---

### "I want to test locally first"
→ **Use Netlify Dev**

```bash
npm install -g netlify-cli
echo "ANTHROPIC_API_KEY=sk-ant-..." > .env
netlify dev
```

Open http://localhost:8888

---

## ❓ Why Can't I Just Open The HTML File?

**CORS Security** - Browsers block direct API calls to protect your API key.

**What works:**
- ✅ Demo (pre-generated content)
- ✅ Netlify deployment (serverless functions)
- ✅ Netlify Dev (local server)

**What doesn't work:**
- ❌ Opening HTML file directly with your API key

---

## 📁 File Guide

| File | What It Does | When To Use |
|------|-------------|-------------|
| `she-speaks-demo.html` | Pre-loaded sample | Want to see it now |
| `she-speaks-enhanced.html` | Full production app | Deploy to Netlify |
| `she-speaks-local.html` | Explainer page | Opened by mistake |
| `README.md` | Complete documentation | Need details |

---

## 🚀 Recommended Path:

1. **Open demo** → See how it works
2. **Deploy to Netlify** → Get full functionality
3. **Explore & customize** → Make it yours

---

## 💡 Features You Get:

**Four Interpretive Lenses:**
- 🕊 Abide 365 - Devotional reflection
- 🧩 FractaSelf - Identity archetype
- 🌈 The Arc - Mythic retelling
- 🪞 Satirical Quill™ - Holy roast

**Export Options:**
- PDF journal pages
- Podcast scripts
- Group study guides

**Sources:**
- Modern translations (NIV, NLT, ESV, NRSV)
- Ethiopian Orthodox Bible
- Apocryphal texts
- No King James Version

---

## 🆘 Troubleshooting:

**"Unable to generate interpretation"**
→ You're hitting CORS. Use Netlify deployment or netlify dev.

**"White screen"**
→ You might need to refresh. Or use the demo version.

**"Where's my API key?"**
→ Get free key at console.anthropic.com

---

## 📧 Questions?

Check README.md for full documentation.

**Creator:** Adenike Omoregbee  
**Email:** fractaself@gmail.com

---

© Adenike Omoregbee. All rights reserved.
