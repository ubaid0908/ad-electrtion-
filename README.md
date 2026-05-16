# ⚡ AD ELECTRICIAN — Website

A modern, animation-rich, fully responsive multi-page website for **AD Electrician** built with pure HTML, CSS & JavaScript (no frameworks required). Inspired by "Sleepy Interactions" style — featuring custom cursor, smooth scroll reveals, magnetic buttons, marquee, animated counters and more.

## 📁 Folder Structure

```
ad-electrician/
├── index.html          # Home page
├── services.html       # Services page
├── about.html          # About / Team page
├── projects.html       # Portfolio
├── contact.html        # Contact form
├── css/
│   └── style.css       # All styling
├── js/
│   └── script.js       # All interactions & animations
└── README.md           # This file
```

## 🚀 How to Run Locally (Visual Studio Code)

1. **Open the folder in VS Code**
   - Open VS Code → File → Open Folder → select `ad-electrician`

2. **Install "Live Server" extension** (one-time)
   - Click the Extensions icon on the left sidebar (or press `Ctrl+Shift+X`)
   - Search for **"Live Server"** by Ritwick Dey
   - Click **Install**

3. **Run the website**
   - Right-click on `index.html` in the Explorer panel
   - Select **"Open with Live Server"**
   - Browser will open at `http://127.0.0.1:5500/index.html`

## 🌐 How to Deploy

### Option A — GitHub Pages (Free, Recommended)
1. Create a new GitHub repo (e.g., `ad-electrician-site`)
2. Upload all files
3. Repo → Settings → Pages → Source: `main` branch → `/root`
4. Site live at `https://YOUR-USERNAME.github.io/ad-electrician-site/`

### Option B — Netlify (Drag & Drop)
1. Go to https://app.netlify.com/drop
2. Drag the entire `ad-electrician` folder into the box
3. Done! Free subdomain provided instantly.

### Option C — Vercel
1. Sign up at vercel.com → Import Project → Drag folder
2. Click Deploy

## ✨ Features

- ⚡ **Custom Cursor** — yellow dot + smooth following outline
- 🎬 **Loading Screen** — animated bolt with progress bar
- 🎯 **Magnetic Buttons** — buttons follow your cursor
- 📜 **Scroll Reveal** — content fades in as you scroll
- 🔢 **Animated Counters** — stats count up smoothly
- 🔁 **Marquee** — infinite scrolling tagline strip
- 🧭 **Responsive Navbar** — hamburger menu on mobile
- 🎨 **Hover Service Cards** — yellow flood-fill effect
- 📱 **Mobile First** — works on all screen sizes
- ♿ **Accessible** — semantic HTML & ARIA labels
- 🌐 **SEO Ready** — meta tags & clean structure

## 🎨 Color Palette

| Color  | HEX        | Usage              |
|--------|------------|--------------------|
| Yellow | `#FFD60A`  | Accent, CTAs       |
| Black  | `#0A0A0A`  | Background         |
| Dark   | `#111111`  | Cards              |
| White  | `#F5F5F5`  | Body text          |
| Gray   | `#888888`  | Secondary text     |

## 📝 What to Edit (Before Going Live)

Search & replace the following placeholders in all HTML files:

- `+1 (234) 567-890` → your real phone
- `hello@adelectrician.com` → your real email
- `123 Voltage Street, City Center` → your real address
- Social media links in `<footer>` → your actual profiles
- In `contact.html` → replace the map placeholder with a Google Maps embed
- Update team names in `about.html`
- Update testimonial names & quotes in `index.html`

## 🔌 Form Submission

The contact form currently uses a JS demo (success message). To make it actually send emails, use one of:

- **Formspree** (`https://formspree.io`) — easiest
- **Netlify Forms** — auto if hosted on Netlify
- **EmailJS** (`https://emailjs.com`) — client-side

Example with Formspree:
```html
<form action="https://formspree.io/f/YOUR-ID" method="POST">
```

## 📞 Need Help?

Built with ⚡ for AD Electrician.
