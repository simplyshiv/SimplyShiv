# SimplyShiv Immigration Inc. — Website

A complete 5-page website for SimplyShiv Immigration Inc., built with HTML, CSS, and JavaScript. Ready to deploy on GitHub Pages.

## Files
- `index.html` — Home page
- `about.html` — About Us
- `services.html` — Services
- `faq.html` — FAQ
- `contact.html` — Contact Form
- `style.css` — All styles
- `main.js` — Interactivity (nav, FAQ accordion, contact form)

---

## How to Deploy on GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click the **+** icon (top right) → **New repository**
3. Name it: `simplyshiv-immigration` (or any name you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the Files
1. In your new repo, click **Add file** → **Upload files**
2. Drag and drop ALL the website files into the upload area:
   - index.html, about.html, services.html, faq.html, contact.html
   - style.css, main.js
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repository **Settings** tab
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and **/ (root)**
5. Click **Save**
6. Wait 1–2 minutes. Your site will be live at:
   `https://YOUR-USERNAME.github.io/simplyshiv-immigration/`

---

## Connect Your GoDaddy Domain

### Step 1 — Add Your Domain in GitHub Pages
1. In your repo **Settings → Pages**
2. Under **Custom domain**, type your domain (e.g. `www.simplyshivimmigration.com`)
3. Click **Save**

### Step 2 — Update GoDaddy DNS
1. Log in to GoDaddy → **My Products** → **DNS**
2. Add/update these records:

**For the `www` subdomain:**
| Type | Name | Value |
|------|------|-------|
| CNAME | www | YOUR-USERNAME.github.io |

**For the root domain (apex):**
| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

3. Save and wait 10–30 minutes for DNS to propagate
4. GitHub will automatically provision a free SSL certificate

---

## Setting Up the Contact Form

The contact form uses [Formspree](https://formspree.io) — free for up to 50 submissions/month.

1. Go to [formspree.io](https://formspree.io) and sign up (free)
2. Create a new form → it will give you a form ID like `xpwzabcd`
3. Open `contact.html` and find this line:
   ```
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
4. Replace `YOUR_FORM_ID` with your actual Formspree form ID
5. Re-upload `contact.html` to GitHub

Form submissions will be sent to your email automatically!

---

## Customization Tips

- **Business name/email:** Search for `SimplyShiv` or `SimplyShivImmigration` across all files to update
- **Colors:** Edit the CSS variables at the top of `style.css` (`:root` section)
- **Adding a phone number:** Search for `📍 Canada` and add a phone line below it
- **Logo:** Replace the `✦` symbol with an actual image `<img>` tag if you get a logo designed

---

© 2025 SimplyShiv Immigration Inc.
