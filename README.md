# 🗂 Data Analytics Portfolio — GitHub Pages

A clean, dark-themed analytics portfolio built with pure HTML/CSS/JS. No frameworks, no build step — just push and it's live.

---

## 🚀 How to Deploy in 5 Minutes

### Step 1 — Create the repository
1. Go to [github.com](https://github.com) → **New repository**
2. Name it exactly: `yourusername.github.io`  
   *(replace `yourusername` with your actual GitHub username)*
3. Set to **Public**, click Create

### Step 2 — Upload files
Upload these files to the root of your repo:
- `index.html` ← your main portfolio page
- `_config.yml` ← site metadata
- `README.md` ← this file (optional)

You can drag-and-drop them directly on GitHub.com.

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under "Source" → select **Deploy from branch**
3. Choose `main` branch, `/ (root)` folder
4. Click **Save**

Your site will be live at `https://yourusername.github.io` within 1–2 minutes. ✅

---

## ✏️ How to Customize

### Swap your personal info
Search the `index.html` file for these placeholders and replace them:

| Placeholder | Replace with |
|---|---|
| `Your Name` | Your actual name |
| `YourName.dev` | e.g. `janedoe.dev` |
| `[Your Previous Role]` | e.g. `Marketing Analyst` |
| `[X years]` | e.g. `3 years` |
| `[Previous Field]` | e.g. `market research` |
| `you@email.com` | Your email |
| `yourprofile` | Your LinkedIn username |
| `yourusername` | Your GitHub username |
| Impact numbers (5+, 10M+, etc.) | Your real metrics |

### Update projects
Each project card in the `projects-grid` div follows this structure:
```html
<div class="project-card">
  <div class="project-img">[ Screenshot placeholder ]</div>
  <div class="project-body">
    <div class="project-tools">
      <span class="project-tag">SQL</span>
      <!-- add more tags -->
    </div>
    <div class="project-title">Your Project Title</div>
    <p class="project-desc">Your 2–3 sentence description...</p>
    <a href="https://github.com/yourusername/repo" class="project-link">View on GitHub →</a>
  </div>
</div>
```

### Add project images
1. Create a folder `assets/images/` in your repo
2. Upload screenshots of your projects (keep them under 300KB each for fast loading)
3. Replace `<div class="project-img">[ Screenshot placeholder ]</div>` with:
```html
<img class="project-img" src="assets/images/your-project.webp" alt="Project name"/>
```

### Change accent color
Find `:root` at the top of the CSS and edit:
```css
--accent:  #00d4aa;  /* teal — change to any color */
--accent2: #4f8ef7;  /* blue */
```

---

## 📁 File Structure

```
yourusername.github.io/
├── index.html          ← main portfolio (single page)
├── _config.yml         ← GitHub Pages metadata
├── README.md           ← this file
└── assets/
    └── images/         ← project screenshots (add these)
```

---

## 💡 Tips from Ria's Approach
- **Lead with outcomes, not tools.** "Identified $11.7M retention opportunity" beats "Used Python."
- **Keep metrics honest.** Only count what you actually did.
- **Consistent card layouts** let visitors scan and compare without re-orienting.
- **Update often.** Add a new project card whenever you finish something — takes 10 minutes.

---

*Built with HTML, CSS & GitHub Pages · No frameworks, no dependencies, no cost.*
