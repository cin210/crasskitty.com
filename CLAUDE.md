# crasskitty.com

Static link page for CrassKitty, hosted on GitHub Pages with a custom domain.

## Project structure

- `index.html` — the entire site (HTML + CSS, no JS, no build step)
- `profile.jpg` — profile photo (circular crop applied via CSS)
- `og-image.png` — social preview card (1200x630) shown in iMessage, Twitter, Discord, etc.
- `CNAME` — custom domain config for GitHub Pages (do not delete)

## How it works

Push to `master` and GitHub Pages deploys automatically. No build tools, no dependencies.

## Common changes

**Add a link:** Add a new `<a class="link-button">` inside the `<div class="links">` section.

**Remove a link:** Delete the entire `<a class="link-button">...</a>` block.

**Change bio:** Edit the text inside `<div class="bio">`.

**Change profile photo:** Replace `profile.jpg` (keep the filename, or update the `<img src>` tag).

**Change background color:** Replace `#FF00B2` everywhere it appears.

**Update OG preview image:** Replace `og-image.png` with a new 1200x630 PNG. This is what shows up when the link is shared on social media or in messages.

## Style notes

- Background: `#FF00B2` (hot pink)
- Buttons: white outline, white text, slightly rounded (`border-radius: 8px`)
- Font: Inter (loaded from Google Fonts)
- All text is white

## Domain & hosting

- Domain: crasskitty.com (managed via Cloudflare, DNS-only mode)
- Hosting: GitHub Pages from `master` branch of `cin210/crasskitty.com`
- HTTPS enforced via GitHub Pages
- Commission button uses a `mailto:` link to `contact.crasskitty@gmail.com`
