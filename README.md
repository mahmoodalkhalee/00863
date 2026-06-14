<<<<<<< HEAD
# Alka10 Group — Website

Static holding company website for **Alka10 Group**.  
Two files. No build tools. No dependencies. Paste and open.

---

## Stack

- Pure HTML + CSS (no framework, no JS)
- Google Fonts: Cormorant Garamond + Inter (loaded via CDN)
- Fully responsive, mobile-first

---

## File Structure

```
alka10group/
├── index.html
├── style.css
└── README.md
```

---

## Setup

1. Drop both files in a folder called `alka10group/`
2. Open `index.html` in your browser — it works immediately
3. To preview with live reload in VS Code:
   - Install the **Live Server** extension
   - Right-click `index.html` → **Open with Live Server**

---

## Customization Quick Reference

| What to change | Where |
|---|---|
| Email address | `index.html` → contact section `href` + visible text |
| Division descriptions | `index.html` → `.division-card` blocks |
| Division status labels | `index.html` → `.division-status` spans |
| Gold accent color | `style.css` → `--gold` token |
| Hero tagline | `index.html` → `.hero-headline` |
| Founded year / location | `index.html` → `.hero-eyebrow` |

---

## CSS Design Tokens

All core values live at the top of `style.css` under `:root {}`:

```css
--black         /* page background     #0A0A0A */
--surface       /* card hover bg       #111111 */
--white         /* primary text        #F0EDE6 */
--white-dim     /* secondary text      #888888 */
--gold          /* accent color        #C9A84C */
--gold-dim      /* muted accent        #8A6E2F */
--font-display  /* Cormorant Garamond  (serif)  */
--font-body     /* Inter               (sans)   */
```

Change `--gold` to adapt the color scheme to any brand accent.

---

## Deploying

**Netlify (fastest):**
1. Go to [netlify.com](https://netlify.com)
2. Drag the `alka10group/` folder into the deploy zone
3. Done. You get a live URL instantly.

**GitHub Pages:**
1. Push the folder to a GitHub repo
2. Go to Settings → Pages → Deploy from `main` branch
3. Select `/root` as source

**Custom domain:**
- Point your domain's DNS A record to your host
- Update the email in the contact section to your real address

---

## To-Do (when ready to expand)

- [ ] Add favicon (`favicon.ico` or `.svg`)
- [ ] Connect real contact email or Tally/Typeform form
- [ ] Add Open Graph meta tags for social sharing preview
- [ ] Add a logo SVG in the nav (replace text)
- [ ] Add individual division pages (one per division)

---

*Alka10 Group — Kano, Nigeria*
=======
# 00863
Assignment of Prof bashir galadanchi
>>>>>>> 1d70a399bafff382ca5c9e64014677101b410328
# -00863
