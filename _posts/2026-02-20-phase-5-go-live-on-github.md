---
layout: wrapper
title: "Phase 5: Deployment (Go Live on GitHub Pages)"
date: 2026-02-20
author: Ashok
---

You made it to the final phase! Your blog looks great on your computer, but now it is time to share it with the world. 

We will use **GitHub Pages** to host your website. It is incredibly fast, highly secure, and 100% free forever. Let's get your site on the internet! 🌍

---

## 📦 Step 1: Create a GitHub Repository

Think of a repository (repo) as a folder on GitHub's servers where your website's files will live.

- [ ] Log in to your account at [GitHub.com](https://github.com).
- [ ] Click the `+` icon in the top right corner and select **New repository**.
- [ ] Name your repository (e.g., `my-developer-blog`).
- [ ] Make sure it is set to **Public** so people can see your site.

> ⚠️ **CRITICAL STEP:** Do **NOT** check the boxes to add a README, `.gitignore`, or license. You want this repository to be completely empty to start!

- [ ] Click the green **Create repository** button.
- [ ] On the next page, copy the repository URL (it will look something like `https://github.com/yourusername/my-developer-blog.git`).

---

## 🚀 Step 2: Push Your Local Code to GitHub

Now, we need to send the files from your computer up to that empty folder on GitHub. We will use those Git tools we installed in Phase 1.

- [ ] Go back to **VS Code**.
- [ ] Open your terminal (`Terminal` > `New Terminal`) and make sure you are in your blog's main folder.
- [ ] If your Jekyll server is running, stop it with `Ctrl + C`.

Run the following commands one by one, pressing `Enter` after each:

**1. Initialize Git in your folder:**
```bash
git init
```

**2. Create a special branch for hosting (GitHub looks for this exact name):**
```bash
git checkout -b gh-pages
```

**3. Stage all your files to be uploaded:**
```bash
git add .
```

**4. Save the snapshot with a message:**
```bash
git commit -m "My first blog publish"
```

**5. Link your local folder to GitHub (replace the URL with the one you copied):**
```bash
git remote add origin [https://github.com/yourusername/my-developer-blog.git](https://github.com/yourusername/my-developer-blog.git)
```

**6. Push your files to the internet:**
```bash
git push -u origin gh-pages
```

---

## 🌐 Step 3: Enable GitHub Pages

Your code is now on GitHub! The very last step is telling GitHub to turn that code into a live website.

- [ ] Go back to your repository on **GitHub.com** in your browser and refresh the page. You should see all your files!
- [ ] Click on the **Settings** tab (the gear icon) near the top.
- [ ] On the left sidebar, scroll down and click on **Pages**.
- [ ] Under "Build and deployment", look for the "Source" dropdown. Ensure it says **Deploy from a branch**.
- [ ] Under "Branch", ensure the dropdown says **`gh-pages`** and the folder says `/ (root)`. 



> ⏳ **Patience:** It takes GitHub about 1 to 2 minutes to build your site the first time. 

- [ ] Refresh the page after a minute or two. At the top of the Pages section, you will see a box that says: **"Your site is live at `https://yourusername.github.io/...`"**

🎉 **CONGRATULATIONS!** 🎉
Click that link! You are now the proud owner of a live, lightning-fast developer blog. You can share this URL on your resume, your social media, or your YouTube channel. 

*Whenever you want to add a new post in the future, just write it in VS Code, and run `git add .`, `git commit -m "new post"`, and `git push` to instantly update your live site!*