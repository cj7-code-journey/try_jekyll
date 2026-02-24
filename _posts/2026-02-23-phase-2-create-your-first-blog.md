---
layout: post
title: "Phase 2: First Look (Create & View Your Blog)"
date: 2026-02-23
---

Now that your workspace is ready, the fun part begins! In this phase, we are going to generate your entire blog using a single command. 

You don't need to write any HTML or CSS—Jekyll will create a fully functioning website with a beautiful default theme called **Minima**. Let's get it running! 🚀

---

## 🏗️ Step 1: Generate Your Blog

First, we need to tell Jekyll to build the foundation of our site. 

- [ ] Open your **Terminal** (or Command Prompt).
- [ ] Navigate to the folder where you want to keep your project (e.g., your Desktop or Documents folder).
- [ ] Type the following command and press `Enter`:

```bash
jekyll new my_personal_blog
```

> 💡 **What just happened?** Jekyll just created a new folder called `my_personal_blog` and filled it with all the necessary files, layouts, and stylesheets to run a blog.

---

## 🟢 Step 2: Start the Local Server

Before we put the site on the internet, we want to view it locally on our own computer. This allows us to test things and write posts privately.

- [ ] In your terminal, move inside your new blog's folder by running:

```bash
cd my_personal_blog
```

- [ ] Now, start the Jekyll local server by running this command:

```bash
bundle exec jekyll serve
```

> ⏳ **Note:** Your terminal will show some text and eventually say `Server address: http://127.0.0.1:4000/`. This means your site is officially running! Keep this terminal window open.

---

## 👀 Step 3: View Your Live Site

Let's see what you just built!

- [ ] Open your favorite web browser (Chrome, Edge, Safari, etc.).
- [ ] In the address bar at the top, type exactly this and press `Enter`:

```text
http://localhost:4000
```

🎉 **Congratulations!** You should now see your brand new blog live on your screen. It will have a default "Welcome to Jekyll!" post already waiting for you.



---

### 🛑 How to Stop the Server
When you are done working on your blog for the day, you can stop the local server.
- [ ] Go back to your terminal window.
- [ ] Press `Ctrl + C` on your keyboard. 

*In Phase 3, we will open this project in VS Code and personalize the site with your name, description, and social links!*