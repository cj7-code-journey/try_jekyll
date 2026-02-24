---
layout: post
title: "Phase 4: Content Management (Start Writing)"
date: 2026-02-23
---

The setup is completely finished! From this day forward, you will spend 99% of your time in this phase. You never have to touch configuration files again. 

Whenever you want to write a new blog post, simply create a plain text file. Let's learn how to write posts, save drafts, and add images. 📝

---

## ✍️ Step 1: Write Your First Post

Articles or blog posts are the core of a Jekyll site. To create a new post, you need to add a file inside the `_posts` directory.

- [ ] In VS Code, open the **`_posts`** folder.
- [ ] Create a new file. **You must name your file using this exact format:** `YEAR-MONTH-DAY-title.md`.
  * *Example:* `2026-02-24-my-first-post.md`

- [ ] At the very top of your new file, add your **Front Matter**. This tells Jekyll the title and layout of your post. Paste this exactly:

```yaml
---
layout: post
title: "My First Post"
---
```

- [ ] Below the second set of dashes (`---`), start writing your content using standard Markdown! You can use `#` for headings, `*` for bullet points, and `**` for bold text.
- [ ] Save the file (`Ctrl + S`). If your local server is running, Jekyll will automatically build the page and add it to your homepage!

---

## 🕵️ Step 2: Working with Drafts

Sometimes you want to start writing a post but are not ready to publish it to the world yet. That is where drafts come in.

- [ ] Create a new folder in your main project directory (right next to `_posts`) and name it **`_drafts`**.
- [ ] Create a markdown file inside this folder (e.g., `future-post.md`). Notice that you **do not** need the date in the filename for drafts!
- [ ] Write your post with the standard Front Matter at the top.

> 💡 **Pro Tip:** By default, Jekyll hides drafts. To preview your drafts on your local server to see how they look before publishing, you need to start your server with a special flag. 

- [ ] Stop your server (`Ctrl + C`) and restart it with this command:

```bash
bundle exec jekyll serve --drafts
```

Now, your drafts will appear on your local homepage as the newest posts!

---

## 🖼️ Step 3: Adding Images to Posts

A text-only blog can be boring. Let's add some images!

- [ ] In your main project directory, create a new folder called **`assets`**.
- [ ] Inside the `assets` folder, create another folder called **`images`**.
- [ ] Drag and drop a picture (like `my-photo.jpg`) into that `images` folder.

To show the image inside your blog post, use this simple Markdown syntax anywhere in your post:

```markdown
![A description of my photo for screen readers](/assets/images/my-photo.jpg)
```

Save the file, and the image will instantly appear perfectly formatted in your post!

---

🎉 **You are officially a blogger!** You know how to configure your site, write posts, save drafts, and add images. 

*In Phase 5, the final phase of this series, we will take your local site and deploy it live to the internet for free using GitHub Pages!*