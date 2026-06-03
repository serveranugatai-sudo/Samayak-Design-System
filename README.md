# Samayak — Design System

> Anugat AI · Product design language for the Samayak academic operations platform.

**Live demo:** [deploy via GitHub Pages — see below]

---

## What's inside

| File | Purpose |
|------|---------|
| `index.html` | The complete design system — self-contained, zero dependencies |

Single HTML file. No build step. No npm. Opens in any browser offline too.

---

## Deploy to GitHub Pages (< 2 minutes)

### Option A — New repo via GitHub website

1. Go to [github.com/new](https://github.com/new)
2. Name it something like `samayak-design-system`
3. Keep it **Public** (required for free GitHub Pages)
4. Click **Create repository**
5. Upload `index.html` and `README.md` via the **"uploading an existing file"** link
6. Go to **Settings → Pages**
7. Under **Source**, select **Deploy from a branch → main → / (root)**
8. Hit **Save** — your site will be live at:
   ```
   https://<your-username>.github.io/samayak-design-system/
   ```

### Option B — Push via terminal (git)

```bash
# 1. Create a folder and init git
mkdir samayak-design-system
cd samayak-design-system

# 2. Drop in the files
cp /path/to/index.html .
cp /path/to/README.md .

# 3. Push to GitHub
git init
git add .
git commit -m "feat: Samayak design system v1.0"
git branch -M main
git remote add origin https://github.com/<your-username>/samayak-design-system.git
git push -u origin main

# 4. Enable Pages in GitHub repo settings
#    Settings → Pages → Source: main / (root) → Save
```

---

## Share with your team

Once deployed, send the URL directly:

- **New joiners** — read it first before touching Figma
- **Developers** — reference tokens: colours, spacing, radius, shadows
- **Hiring assessments** — give candidates the URL as the brief spec sheet

---

## Update the design system

1. Edit `index.html` locally
2. `git add index.html && git commit -m "update: ..." && git push`
3. GitHub Pages auto-refreshes within ~30 seconds

---

## Design tokens at a glance

| Token | Value |
|-------|-------|
| Font | Figtree (Google Fonts) |
| Gradient | `linear-gradient(105deg, #256199 0%, #3DA1FF 100%)` |
| App canvas | `#CFE1F5` |
| Card surface | `#FFFFFF` |
| Ink / text | `#232635` |
| Muted text | `#7C8294` |
| Border radius (card) | `22px` |
| Border radius (pill) | `999px` |
| Shadow (md) | `0 14px 40px rgba(37,97,153,.12)` |

---

*Anugat AI · Samayak v1.0 · June 2026*
