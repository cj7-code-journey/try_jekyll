---
layout: wrapper
title: "Phase 3: Personalization (Make Your Blog Yours)"
date: 2026-02-22
author: Ashok
---

Right now, your blog has default placeholder text like "Your awesome title". Let's change that and make this website truly yours!

The best part about the default Jekyll Minima theme is that you don't need to know any web design. You just update one text file, and Jekyll updates your entire website automatically. Let's do it! 🎨

---

## 📂 Step 1: Open Your Project in VS Code

We need to open the folder we created in Phase 2 so we can edit the files.

- [ ] Open **VS Code**.
- [ ] Click on `File` > `Open Folder...` (or `Open...` on Mac).
- [ ] Find and select the `my_personal_blog` folder you created earlier.
- [ ] You should now see a list of files and folders on the left side of your screen. 

---

## ⚙️ Step 2: Edit the Configuration File

Jekyll has a master settings file called `_config.yml`. This file controls the global details of your website.

- [ ] In the left sidebar of VS Code, click on the **`_config.yml`** file to open it.
- [ ] Scroll down and look for the basic site settings. Change the text inside the quotes to match your own details. 

Update these lines:

```yaml
title: "My Awesome Tech Blog"
email: "your-email@example.com"
description: "Documenting my coding journey, projects, and daily notes."
author: "Your Name"
```

> 💡 **Tip:** Be careful not to delete the spaces or the colons (`:`)! YAML files are very strict about spacing.

---

## 🔗 Step 3: Add Your Social Links

Scroll down a little further in the `_config.yml` file, and you will find a section for social media. Jekyll's default theme will automatically create nice clickable icons in your website's footer for any accounts you link here!

- [ ] Find the social links section and add your usernames (just the username, not the full URL):

```yaml
twitter_username: yourtwitterhandle
github_username:  yourgithubname
# You can also add linkedin, dribbble, etc., if the theme supports it!
```

- [ ] When you are done making changes, save the file by pressing `Ctrl + S` (Windows) or `Cmd + S` (Mac).


---

## 🔄 Step 4: Restart Your Server

Here is a very important Jekyll rule: **Whenever you change the `_config.yml` file, you must restart your server to see the changes.** - [ ] Open your terminal inside VS Code (Go to `Terminal` > `New Terminal` at the top).
- [ ] If your server is currently running, stop it by pressing `Ctrl + C`.
- [ ] Start it again by typing:

```bash
bundle exec jekyll serve
```

- [ ] Go back to your browser and refresh the page at `http://localhost:4000`.

🎉 **Boom!** Your name, your blog title, your description, and your social links are now live on the site. The header and footer have updated automatically.

*In Phase 4, we will finally learn how to write our very first blog post using simple Markdown!*