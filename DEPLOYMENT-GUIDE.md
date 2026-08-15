# 🚀 GitHub Deployment Guide

Step-by-step guide to push your Sweet Treats project to GitHub.

---

## 📋 Prerequisites

1. ✅ Git installed on your computer
2. ✅ GitHub account created
3. ✅ Your project ready (you have this!)

---

## 🌐 Step 1: Create GitHub Repository

### Option A: Using GitHub Website (Easiest)

1. **Go to GitHub**: https://github.com
2. **Sign in** to your account
3. **Click** the **"+"** icon (top-right) → **"New repository"**
4. **Fill in details**:
   - Repository name: `sweet-treats` (or any name you like)
   - Description: `A fully functional bakery e-commerce website`
   - Visibility: **Public** (so others can see it)
   - ⚠️ **DO NOT** check "Add README" (we already have one)
   - ⚠️ **DO NOT** check "Add .gitignore" (we already have one)
   - ⚠️ **DO NOT** choose a license (we already have LICENSE)
5. **Click** "Create repository"

### Option B: Using GitHub CLI (Advanced)

```bash
# If you have GitHub CLI installed
gh repo create sweet-treats --public --source=. --remote=origin
```

---

## 💻 Step 2: Connect & Push to GitHub

### Open Terminal/PowerShell in Your Project

**Option 1**: In VS Code
- Press `Ctrl + ~` (opens terminal at bottom)

**Option 2**: In Windows
- Navigate to `d:\SweetTreats\SweetTreats\SweetTreats`
- Right-click → "Open in Terminal" or "Open PowerShell here"

---

### Run These Commands (One by One):

```bash
# 1. Make sure you're in the project directory
cd d:\SweetTreats\SweetTreats\SweetTreats

# 2. Check Git status (optional - to see what files will be pushed)
git status

# 3. Add all files to staging
git add .

# 4. Commit changes
git commit -m "Initial commit - Sweet Treats Bakery Website"

# 5. Add your GitHub repository as remote
# Replace YOUR_USERNAME with your actual GitHub username
git remote add origin https://github.com/YOUR_USERNAME/sweet-treats.git

# 6. Check if remote was added correctly
git remote -v

# 7. Push to GitHub
git push -u origin main
```

---

## 🔑 Authentication

When you push, GitHub will ask for credentials:

### Option 1: Using GitHub Token (Recommended)
1. Go to GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Click "Generate new token (classic)"
3. Select scopes: `repo` (full control)
4. Copy the token
5. Use token as password when pushing

### Option 2: Using GitHub Desktop
1. Download GitHub Desktop
2. File → Add Local Repository
3. Select your project folder
4. Publish to GitHub

---

## ✅ Verify Upload

1. Go to your GitHub repository: `https://github.com/YOUR_USERNAME/sweet-treats`
2. You should see all your files!
3. Check that README.md displays nicely

---

## 🌍 Step 3: Enable GitHub Pages (Free Hosting!)

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**:
   - Branch: `main`
   - Folder: `/ (root)`
   - Click **Save**
5. Wait 1-2 minutes
6. Your site will be live at:
   ```
   https://YOUR_USERNAME.github.io/sweet-treats/html/index.html
   ```

---

## 📝 Update README with Your Info

Edit `README.md` and replace:
- `YOUR_USERNAME` → Your GitHub username
- `Your Name` → Your actual name
- `your.email@example.com` → Your email
- Add your live demo link after GitHub Pages is set up

Then push again:
```bash
git add README.md
git commit -m "Updated README with personal info"
git push
```

---

## 🎯 Common Issues & Solutions

### Issue: "fatal: remote origin already exists"
**Solution**:
```bash
git remote remove origin
git remote add origin https://github.com/YOUR_USERNAME/sweet-treats.git
```

### Issue: "fatal: not a git repository"
**Solution**:
```bash
git init
git add .
git commit -m "Initial commit"
```

### Issue: Branch name is "master" instead of "main"
**Solution**:
```bash
git branch -M main
git push -u origin main
```

### Issue: Authentication failed
**Solution**: Use GitHub Personal Access Token instead of password

---

## 🔄 Future Updates

When you make changes to your project:

```bash
# 1. Check what changed
git status

# 2. Stage changes
git add .

# 3. Commit with a message
git commit -m "Description of what you changed"

# 4. Push to GitHub
git push
```

---

## 🎉 That's It!

Your project is now on GitHub! Share the link:
```
https://github.com/YOUR_USERNAME/sweet-treats
```

And the live website:
```
https://YOUR_USERNAME.github.io/sweet-treats/html/index.html
```

---

## 📚 Additional Resources

- [GitHub Docs](https://docs.github.com)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [GitHub Pages Guide](https://pages.github.com)

---

**Questions?** Check the GitHub documentation or ask the community!

Good luck! 🚀
