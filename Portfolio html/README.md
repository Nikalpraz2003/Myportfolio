# 🚀 Nikal Prajapati - Portfolio Website

A modern, responsive portfolio website showcasing skills, projects, and achievements.

## 📁 Project Structure

```
Portfolio html/
│
├── index.html              # Main HTML file (your portfolio page)
│
├── assets/
│   ├── css/
│   │   └── style.css       # All styles and design
│   │
│   ├── js/
│   │   └── script.js       # Interactive features (menu, scroll effects)
│   │
│   ├── cv/
│   │   └── Nikal_Prajapati_CV.pdf.pdf  # Your CV/Resume
│   │
│   └── images/
│       └── pp.png          # Your profile photo
│
└── README.md               # This file
```

---

## 🎯 Quick Start (Super Easy!)

### Option 1: Just Open the File
1. Double-click `index.html`
2. Your portfolio opens in your browser!

### Option 2: Live Preview (For Development)
1. Right-click `index.html` in VS Code
2. Select "Open with Live Server" (if you have the extension)
3. Changes auto-refresh!

---

## ✏️ How to Update Your Portfolio

### 📸 Update Your Photo
1. Replace `assets/images/pp.png` with your new photo
2. Keep the name as `pp.png` OR
3. Update the image path in `index.html` (line ~72)

### 📄 Update Your CV
1. Replace `assets/cv/Nikal_Prajapati_CV.pdf.pdf` with your new CV
2. Rename your CV to match the existing name OR
3. Update the CV path in `index.html` (line ~34)

### 📝 Update Your Information

#### Change Your Name/Title
- Open `index.html`
- Find line ~17 (header): Change "Nikal Prajapati"
- Find line ~49 (hero section): Change name and title

#### Add/Remove Projects
- Scroll to the Projects section in `index.html` (around line 180)
- Copy an existing project card
- Paste and modify the details

#### Update Skills
- Find the Skills section in `index.html` (around line 160)
- Add/remove `<span class="skill-tag">Your Skill</span>`

#### Change Contact Info
- Scroll to the Contact section (near the bottom)
- Update email, phone, social links

---

## 🎨 Customize Colors

Open `assets/css/style.css` and find this section at the top (lines 7-20):

```css
:root {
    --accent-teal: #00f5d4;     /* Main accent color */
    --accent-blue: #0096ff;     /* Secondary accent */
    --accent-purple: #9333ea;   /* Third accent */
}
```

Change these hex codes to your preferred colors!

---

## 📱 Features

✅ **Fully Responsive** - Works on all devices (phone, tablet, desktop)  
✅ **Mobile Menu** - Hamburger menu for mobile devices  
✅ **Smooth Scrolling** - Clean navigation between sections  
✅ **Active Link Highlighting** - Shows which section you're viewing  
✅ **Download CV Button** - Easy CV download from header  
✅ **Modern Design** - Gradient effects, animations, glassmorphism  
✅ **Fast Loading** - Optimized performance  

---

## 🔧 Troubleshooting

### Photo Not Showing?
- Make sure the image is named `pp.png`
- Check it's in `assets/images/` folder
- Try hard refresh: `Ctrl + Shift + R`

### CV Not Downloading?
- Verify the CV file exists in `assets/cv/` folder
- Check the filename matches in the HTML

### Menu Not Working on Mobile?
- Make sure `assets/js/script.js` is linked in HTML
- Check browser console for errors (F12)

### Styles Not Applying?
- Verify `assets/css/style.css` is linked in HTML head
- Try clearing browser cache

---

## 📂 File Descriptions

| File | What It Does |
|------|-------------|
| `index.html` | Your entire portfolio content - text, structure, sections |
| `assets/css/style.css` | All visual styling - colors, fonts, layouts, animations |
| `assets/js/script.js` | Interactive features - mobile menu, scroll effects, navigation |
| `assets/images/pp.png` | Your profile photo displayed in the hero section |
| `assets/cv/Nikal_Prajapati_CV.pdf.pdf` | Your resume for download |

---

## 🚀 Publishing Your Portfolio

### Option 1: GitHub Pages (Free & Easy)
1. Create a GitHub account
2. Create a new repository named `yourname.github.io`
3. Upload all files
4. Visit `yourname.github.io` - Done!

### Option 2: Netlify (Free & Fast)
1. Go to [netlify.com](https://netlify.com)
2. Drag & drop your portfolio folder
3. Get a free link instantly!

### Option 3: Vercel (Free & Professional)
1. Sign up at [vercel.com](https://vercel.com)
2. Import your project
3. Deploy with one click!

---

## 💡 Quick Edits Cheat Sheet

| Want to change... | Edit this file | Around line |
|------------------|----------------|-------------|
| Your name | index.html | 17, 49 |
| Profile photo | assets/images/pp.png | - |
| Your bio/description | index.html | 50-53 |
| Projects | index.html | 180-300 |
| Skills | index.html | 160-175 |
| Education | index.html | 100-135 |
| Contact info | index.html | 500-550 |
| Colors | assets/css/style.css | 7-20 |
| CV file | assets/cv/ | - |

---

## 📧 Need Help?

If something isn't working:
1. Check the browser console for errors (Press F12)
2. Verify all file paths are correct
3. Make sure all files are in the right folders
4. Try opening in a different browser

---

## 🎓 Built With

- **HTML5** - Structure
- **CSS3** - Styling (with CSS Variables, Flexbox, Grid)
- **Vanilla JavaScript** - Interactivity (no frameworks needed!)
- **Google Fonts** - Inter & Poppins fonts

---

## 📝 License

This is your personal portfolio. Feel free to modify and use it however you like!

---

**Made with ❤️ for showcasing your amazing skills!**
