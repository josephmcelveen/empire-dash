# empire-dash
# McElveen Empire — Command Dashboard

This repo contains a single-page HTML **command dashboard** for Joseph McElveen’s operations:

- Smith’s Facility Solutions (SFS)
- Familia Business Coaching
- AI consulting and content projects
- Personal schedule, budget, and systems

The page is completely self-contained: no external CSS, JS, or build tools required.

---

## Files

- `index.html` — The actual dashboard (dark emerald, high-contrast, mobile-friendly)
- `README.md` — This file (usage and setup instructions)

---

## How to Use

### 1. Open Locally

You can open this file directly on any computer:

1. Download `index.html`
2. Double-click it
3. It will open in your browser

---

### 2. Host on GitHub Pages

To make this dashboard available as a live web page:

1. Create a new GitHub repository (e.g. `empire-dashboard`)
2. Upload:
   - `index.html`
   - `README.md`
3. Go to **Settings → Pages**
4. Under **Source**, choose:
   - “Deploy from a branch”
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

GitHub will build and give you a URL like:

`https://YOUR-USERNAME.github.io/empire-dashboard/`

Bookmark that URL on your phone, tablet, and laptop.

---

## Customization

In `index.html` you can:

- Replace `#PRIMARY_CHAT_LINK_HERE`, `#THURSDAY_DELIVERY_CHAT_LINK_HERE`, etc.
  with:
  - Links to ChatGPT conversations
  - Links to Google Drive docs
  - Links to Notion, Skool, or other tools

- Adjust colors in the `:root` section at the top of the `<style>` block

---

## Notes

- The page is optimized for:
  - Dark mode
  - High contrast text
  - Mobile and desktop
- No JS required; it’s purely structural and visual

If you break something while editing, you can always revert to a previous version via GitHub history.
