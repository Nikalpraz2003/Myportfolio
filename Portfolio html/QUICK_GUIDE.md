# ⚡ QUICK GUIDE - Edit Your Portfolio in 5 Minutes!

## 🎯 Most Common Updates

### 1️⃣ Change Your Photo (30 seconds)
```
1. Go to: assets/images/
2. Replace: pp.png with your photo
3. Keep the same name: pp.png
✅ Done!
```

### 2️⃣ Update Your CV (30 seconds)
```
1. Go to: assets/cv/
2. Replace the PDF file with your new CV
3. Keep the same filename OR update line 34 in index.html
✅ Done!
```

### 3️⃣ Add a New Project (2 minutes)
```
1. Open: index.html
2. Find: <!-- Projects Section --> (around line 180)
3. Copy: Any existing project card
4. Paste: Below the last project
5. Edit: Title, description, tags, and links
✅ Done!
```

### 4️⃣ Update Your Skills (1 minute)
```
1. Open: index.html
2. Find: <!-- Skills Section --> (around line 160)
3. Add: <span class="skill-tag">New Skill</span>
4. Remove: Delete unwanted skill tags
✅ Done!
```

### 5️⃣ Change Colors (1 minute)
```
1. Open: assets/css/style.css
2. Find: :root { (line 7)
3. Change: 
   --accent-teal: #00f5d4;     (your main color)
   --accent-blue: #0096ff;     (your second color)
   --accent-purple: #9333ea;   (your third color)
✅ Done!
```

---

## 🎨 Color Picker
Use these sites to find colors:
- [Coolors.co](https://coolors.co) - Generate color palettes
- [ColorHunt.co](https://colorhunt.co) - Browse beautiful palettes

---

## 📝 Edit Text Content

| What to Change | File | Search for |
|----------------|------|------------|
| Your Name | index.html | "Nikal Prajapati" |
| Your Title | index.html | "Final-Year Computer Science Student" |
| About Me | index.html | "I am a final-year" |
| Email | index.html | "your-email@example.com" |
| Phone | index.html | "+123 456 7890" |
| Social Links | index.html | "linkedin.com/in/yourprofile" |

**How to Search:**
- Press `Ctrl + F` (Windows) or `Cmd + F` (Mac)
- Type what you're looking for
- Replace with your info!

---

## 🚀 View Your Portfolio

### Method 1: Direct Open
```
Double-click: index.html
```

### Method 2: VS Code Live Server
```
1. Right-click: index.html
2. Select: "Open with Live Server"
3. Auto-refreshes on save!
```

---

## 📱 Test on Mobile

1. Open your portfolio on computer
2. Press `F12` (open DevTools)
3. Click the phone icon (top-left)
4. Select different devices to test!

---

## ✅ Before Publishing Checklist

- [ ] Updated your photo (pp.png)
- [ ] Updated your CV
- [ ] Changed all "Nikal Prajapati" to your name
- [ ] Updated contact information
- [ ] Added your projects
- [ ] Listed your actual skills
- [ ] Tested on mobile view (F12 → phone icon)
- [ ] All links work
- [ ] CV downloads correctly

---

## 🔗 Publish Online (FREE!)

### GitHub Pages (Easiest)
```
1. Go to: github.com
2. Create account (if needed)
3. New repository: yourname.github.io
4. Upload all your files
5. Visit: yourname.github.io
```

### Netlify (Fastest)
```
1. Go to: netlify.com
2. Drag & drop your folder
3. Get instant link!
```

---

## 🆘 Quick Fixes

**Photo not showing?**
→ Name must be `pp.png` in `assets/images/`

**CV not downloading?**
→ Check file exists in `assets/cv/`

**Colors look wrong?**
→ Hard refresh: `Ctrl + Shift + R`

**Mobile menu not working?**
→ Make sure `script.js` is in `assets/js/`

---

## 📞 File Structure (Simple View)

```
Your Portfolio/
├── index.html          ← Your content (edit here!)
├── assets/
│   ├── css/
│   │   └── style.css   ← Change colors here
│   ├── js/
│   │   └── script.js   ← Don't touch (it just works!)
│   ├── images/
│   │   └── pp.png      ← Your photo
│   └── cv/
│       └── YourCV.pdf  ← Your resume
```

---

**That's it! You're ready to go! 🎉**

For detailed help, see the full README.md
