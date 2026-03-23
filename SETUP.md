# 🚀 Setup Instructions

This portfolio is ready to use! Follow these simple steps to get started.

## 📁 Files Included

```
Portfolio/
├── README.md              # Main portfolio README (for GitHub)
├── PROFILE-README.md      # GitHub Profile README (copy to dhonmarckherm repo)
├── index.html             # Personal portfolio website
├── CONTRIBUTING.md        # Contribution guidelines
├── LICENSE                # MIT License
└── SETUP.md               # This file
```

## 🎯 Quick Start

### Option 1: GitHub Profile Enhancement

1. **Copy PROFILE-README.md to your special profile repository:**
   ```bash
   # Navigate to your dhonmarckherm repository
   cd dhonmarckhermosura
   
   # Copy the PROFILE-README.md content to README.md
   # This will display on your GitHub profile
   ```

2. **Update your Portfolio repository:**
   ```bash
   cd Portfolio
   
   # Push the new README.md
   git add README.md
   git commit -m "Enhance portfolio with professional README"
   git push
   ```

### Option 2: Deploy Portfolio Website

1. **Using GitHub Pages:**
   - Go to your Portfolio repository settings
   - Navigate to "Pages" section
   - Select main branch as source
   - Your portfolio will be live at: `https://Dhonmarckherm.github.io/Portfolio`

2. **Using Netlify:**
   - Drag and drop the `index.html` file to Netlify Drop
   - Get instant deployment with a live URL

3. **Using Vercel:**
   - Connect your GitHub repository
   - Automatic deployment on every push

### Option 3: Local Development

1. **Open index.html in your browser:**
   ```bash
   # Simply open the file
   start index.html  # Windows
   open index.html   # Mac
   xdg-open index.html  # Linux
   ```

2. **Or use a local server:**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server -p 8000
   ```

## ✏️ Customization

### Update Contact Information

Edit `index.html` and replace:
- `your-email@example.com` with your actual email
- `your-profile` with your LinkedIn username

### Add More Projects

In `README.md` and `index.html`, add new project sections following the existing format:

```markdown
### Project Name
Description of your project

**Tech Stack:** Technologies used

**[View Repository](link-to-your-repo)**
```

### Customize Colors

In `index.html`, modify the CSS variables:

```css
:root {
    --primary-color: #0070d7;      /* Change primary color */
    --secondary-color: #6366f1;    /* Change secondary color */
    --accent: #58a6ff;             /* Change accent color */
}
```

## 📊 GitHub Profile Stats

The portfolio includes dynamic GitHub stats from:
- [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
- [github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- [ghpvc](https://github.com/antonkomarev/github-profile-views-counter)

These will automatically update based on your GitHub activity!

## 🔧 Next Steps

1. ✅ Push all files to your Portfolio repository
2. ✅ Copy PROFILE-README.md to your dhonmarckherm profile repo
3. ✅ Deploy the portfolio website (GitHub Pages recommended)
4. ✅ Update contact information
5. ✅ Share your portfolio with the world!

## 🆘 Need Help?

If you encounter any issues:
1. Check that all files are properly uploaded
2. Ensure your GitHub profile is public
3. Verify repository permissions

## 📝 Tips for Maximum Impact

- ✨ Keep your projects updated
- 📸 Add screenshots to your repositories
- 📝 Write clear README files for each project
- 🔗 Link your portfolio in your GitHub bio
- 🌐 Share on social media and professional networks

---

**Happy Coding! 🚀**

Made with ❤️ for Dhonmarckherm
