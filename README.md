# Corbett Studio — Portfolio & Services Website

My personal website as a freelance web designer. Bright, playful, single-page site built to show off work and bring in client enquiries.

🔗 **Live site:** https://lcorbett419.github.io/corbett-studio/
*(custom domain coming soon)*

---

## What's in here

| File | What it is |
|------|------------|
| `index.html` | The entire website — HTML, styling and scripts all in one self-contained file. No build step, no dependencies. |
| `README.md` | This file. |

That's it. To edit the site, you only ever touch `index.html`.

---

## Quick edits — where to change things

Open `index.html` and use **Ctrl/Cmd + F** to find these:

| To change... | Search for... |
|--------------|---------------|
| Brand / studio name | `Corbett Studio` |
| Email address | `hello@corbettstudio.co.uk` |
| Location | `Newcastle upon Tyne` |
| Pricing | `£___` (three packages) |
| Availability badge | `Available for new projects` |
| Page title / Google description | `<title>` and `name="description"` (near the top) |

After editing on GitHub: scroll down, **Commit changes**, and the live site updates in a minute or so.

---

## Connecting the enquiry form

The contact form needs a free [Formspree](https://formspree.io) account to actually send emails:

1. Sign up and create a new form.
2. Copy the form ID it gives you (looks like `xyzabcde`).
3. In `index.html`, find `YOUR_FORM_ID` and replace it with that ID.
4. Commit. Done — enquiries now land in your inbox.

Until then the form shows a friendly "not connected yet" message instead of failing.

---

## Adding a new project to the Work section

When you finish a client site, copy the existing case-study block in `index.html`
(search for `case-body`) and update the name, description, tags and the live link.
Delete the *"More projects landing soon"* line once you've got a couple.

---

## Hosting

Hosted free on **GitHub Pages**. The repo is the website — pushing a change to
`index.html` deploys it automatically. No server to manage.

### Adding a custom domain (when ready)
1. Buy a domain.
2. Repo → **Settings → Pages → Custom domain** → enter your domain.
3. Add the DNS records your domain provider asks for.
4. Tick **Enforce HTTPS** once it's verified.

---

*Designed & built by me — yes, this site too.*
