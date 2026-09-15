# Himanshu Singh — Portfolio & Essays (`hiimanshu19x.github.io`)

A minimal, modern editorial portfolio website built for **Himanshu Singh**, designed around the narrative transition from **Sports Journalism to AI × Product × Growth**.

- **Tech Stack:** Semantic HTML5, Tailwind CSS (via CDN), Google Fonts (`Newsreader` serif, `Plus Jakarta Sans`, `JetBrains Mono`).
- **Build Step:** **None**. Pure static architecture. Push directly to GitHub and your site is live in seconds.
- **Reading Experience:** Single-page seamless editorial flow with slide-over deep-dive reading drawers for case studies and long-form essays.

---

## 🚀 How to Deploy to GitHub Pages (2 Minutes)

Because your repository name matches `<username>.github.io`, GitHub Pages will automatically host your portfolio at:
👉 **`https://hiimanshu19x.github.io`**

### Step 1: Create the GitHub Repository
1. Go to [github.com/new](https://github.com/new).
2. Set the **Repository name** to:
   ```text
   hiimanshu19x.github.io
   ```
   *(It must match this exact name for automatic root hosting).*
3. Set the repository to **Public**.
4. Leave "Add a README file" and ".gitignore" **unchecked** (we already have them here).
5. Click **Create repository**.

---

### Step 2: Push Your Code to GitHub

Open your terminal in this directory (`hiimanshu19x.github.io`) and run:

```bash
# 1. Initialize git (if not already initialized)
git init -b main

# 2. Add files and commit
git add .
git commit -m "feat: launch modern editorial portfolio for Himanshu Singh"

# 3. Link to your new GitHub repository
git remote add origin https://github.com/hiimanshu19x/hiimanshu19x.github.io.git

# 4. Push to main
git push -u origin main
```

---

### Step 3: Verify GitHub Pages Settings
1. In your GitHub repo, go to **Settings** > **Pages** (in the left sidebar).
2. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/ (root)`
3. Click **Save** (if not already set).
4. Within 30–60 seconds, your site will be live at:
   **`https://hiimanshu19x.github.io`**

---

## ✍️ How to Personalize & Update Content

All content is cleanly organized in `index.html`:

1. **Social & Contact Links**:
   - Search for `https://x.com/hiimanshu19x` to verify your X link.
   - Search for `mailto:himanshu@example.com` to insert your preferred contact email.
   - You can easily add Substack or LinkedIn buttons in the `#contact` section.
2. **Case Studies & Essays**:
   - Scroll down to `<script>` at the bottom of `index.html`.
   - The `articles` JavaScript object stores the full case studies and essays with titles, metadata, tags, and formatted HTML bodies.
   - Edit, add, or replace any story in seconds.
3. **Typography & Styling**:
   - Uses Tailwind utility classes directly in the markup.
   - Custom fonts (`Newsreader`, `Plus Jakarta Sans`, and `JetBrains Mono`) are loaded via Google Fonts in the `<head>`.
