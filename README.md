# My Portfolio

A clean, responsive personal portfolio site hosted on GitHub Pages.

## Quick Setup

### 1. Create your GitHub repo

Go to [github.com/new](https://github.com/new) and create a repo named:

```
yourusername.github.io
```

> Replace `yourusername` with your actual GitHub username. This naming convention tells GitHub to serve it as your site automatically.

### 2. Push this code

```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select `main` branch and `/ (root)` folder
3. Click **Save**

Your site will be live at `https://yourusername.github.io` within a few minutes.

## Customizing

Open `index.html` and update:

- **Your name** — the nav logo and page title
- **Hero text** — your headline and description
- **Projects** — replace the placeholder cards with your real work
- **About** — your bio and skill tags
- **Contact links** — your actual email, GitHub, LinkedIn, etc.

## Connecting Claude

To let Claude push changes directly to this repo, connect the **GitHub connector** in Claude.ai:

1. In a Claude conversation, ask to connect to GitHub
2. Authorize the GitHub integration
3. Claude can then create files, push commits, and manage your site

## License

MIT
