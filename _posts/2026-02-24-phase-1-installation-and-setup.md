---
layout: wrapper
title: "Phase 1: The Setup (Tools & Prerequisites for Your Blog)"
date: 2026-02-24
---

Welcome to the Master Guide for building a free, fast, and beautiful developer blog! 🚀 In this series, we will take you from absolute zero to a live website. 

Before we write any code, we need to prepare our computer. Think of this as setting up your digital workspace. You only have to do this once! Let's break it down step-by-step.

---

## 💻 Step 1: Install a Code Editor

To write our blog posts and edit settings, we need a good text editor. We will use **Visual Studio Code (VS Code)**.

> **💡 Why VS Code?** It is completely free, lightweight, and the industry standard for developers worldwide.

- [ ] Go to [code.visualstudio.com](https://code.visualstudio.com/).
- [ ] Download the installer for your operating system (Windows / Mac / Linux).
- [ ] Run the installer and click "Next" through the default settings.
- [ ] Open VS Code once installed. You will do most of your work right here!

---

## 🐙 Step 2: Set Up Git & GitHub

Git tracks changes in your project, and GitHub is where we will host our website for free.

### 1. Create a GitHub Account
- [ ] Go to [github.com](https://github.com) and sign up for a free account.

> 🎯 **Pro Tip:** Choose a simple, professional username, as this will become part of your website's live URL (e.g., `yourname.github.io`).

### 2. Install Git
- [ ] Go to [git-scm.com/downloads](https://git-scm.com/downloads).
- [ ] Download and install the version for your computer. 
- [ ] *Windows Users:* During installation, just keep clicking "Next" to accept all the recommended default settings.

---

## 💎 Step 3: Install Ruby

Jekyll is the engine that will turn our plain text notes into a real website. Because Jekyll is built on a programming language called **Ruby**, we need to install Ruby first.

### 🪟 For Windows Users:
- [ ] Go to [rubyinstaller.org/downloads](https://rubyinstaller.org/downloads/).
- [ ] Download the recommended version (usually has `WITH DEVKIT` in the name).
- [ ] Run the installer. 

> ⚠️ **Important:** When the installation finishes, it will open a black terminal window asking you to install **MSYS2**. Just press `Enter` to accept the default options and let it complete.

### 🍎 For Mac Users:
Macs often come with Ruby, but it is best to use Homebrew. 
- [ ] Open your terminal and run:

```bash
brew install ruby
```

---

## ⚙️ Step 4: The Final Command (Install Jekyll)

Now that all our tools are installed, let's install Jekyll itself!

1. Open your computer's Terminal (or Command Prompt).
2. Type the following command and press `Enter`:

```bash
gem install jekyll bundler
```

> ⏳ **Note:** This tells your computer to download and install Jekyll and Bundler (a tool that manages Jekyll's dependencies). Wait a minute or two for the installation to finish.

---

🎉 **Awesome job!** Your workspace is completely set up. You now have VS Code, Git, and Jekyll ready to go. 

*In Phase 2, we will run a single command to generate your entire blog and view it live on your computer for the very first time!*