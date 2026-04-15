# crasskitty.com

Your personal link page at [crasskitty.com](https://www.crasskitty.com). One HTML file, no build step, hosted free on GitHub Pages.

## How to make changes

Everything lives in `index.html`. You can edit it directly on GitHub (click the pencil icon) or use Claude Code / Codex / any AI coding tool.

### Common tasks

**Add a new link:**
Find the `<!-- Links -->` section and add a new block like this inside the `<div class="links">`:
```html
<a href="https://your-url-here.com" class="link-button" target="_blank" rel="noopener">
  Button Text Here
</a>
```

**Remove a link:**
Delete the entire `<a class="link-button" ...>...</a>` block for that link.

**Change your bio:**
Find the line `<div class="bio">` and edit the text inside it.

**Change your profile photo:**
Replace `profile.jpg` with a new image (keep the same filename), or update the `<img src="...">` tag to point to the new filename.

**Change the background color:**
Search for `#FF00B2` and replace it with any hex color you want.

**Add a social icon:**
Find the `<div class="socials">` section and add another `<a class="social-icon">` block with an SVG icon inside.

### Using AI tools to edit

If you're using Claude Code, Codex, or Cursor, just tell it what you want in plain english:

- "Add an Instagram link that goes to instagram.com/crasskitty"
- "Change the background to a gradient from pink to purple"
- "Move the OnlyFans link to the top"
- "Add an Instagram icon next to the TikTok icon"

The AI will edit `index.html` for you. Commit and push to deploy.

## How it works

- `index.html` — the entire site (HTML + CSS, no JavaScript needed)
- `profile.jpg` — your profile photo
- `CNAME` — tells GitHub to serve this at crasskitty.com (don't delete this)

When you push changes to the `master` branch, GitHub Pages automatically deploys them. Takes about 30 seconds.
