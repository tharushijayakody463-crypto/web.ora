# Webora — Colombo Web Design & Social Media Agency Website

A responsive, high-converting multi-page agency website built for **Webora** in Colombo, Sri Lanka.

Crafted using **pure semantic HTML5, modern CSS3, and vanilla JavaScript (no frameworks or external dependencies)**. Designed specifically for **GitHub Pages hosting**, fast load speeds on Sri Lankan mobile networks (Dialog & Mobitel 4G/5G), and full accessibility.

---

## 🌟 Key Features

1. **Brand Aesthetic:**
   - Color palette: Royal Navy Blue (`#1e40af`, `#0b192c`), Ash/Slate Grey (`#64748b`, `#f1f5f9`), Crisp White (`#ffffff`), with attractive Cyan (`#06b6d4`) and WhatsApp Emerald Green (`#25d366`).
2. **Hero Section with WhatsApp Booking:**
   - Prominent "Book on WhatsApp" CTA linking directly to WhatsApp hotline with pre-filled inquiry text.
   - Interactive studio preview and agency performance metrics.
3. **Services with Transparent Colombo Pricing:**
   - Starter Launchpad (LKR 45,000 / ~$150 USD)
   - Social Media Growth Engine (LKR 65,000/mo)
   - E-Commerce Powerhouse with PayHere & COD (LKR 150,000 / ~$490 USD)
   - Plus Business Pro, Enterprise Custom, and TikTok Video Retainers.
4. **Why Choose Us:**
   - Sri Lankan local market expertise & Colombo consumer insights.
   - Mobile-first engineering under 1.2s load speed.
   - Direct WhatsApp creative communication with designers.
   - PayHere, WebXpay, and local payment gateway readiness.
5. **Visit Us in Colombo (Physical Studio Section):**
   - Studio address: Level 4, Webora Studio Building, No. 425 Galle Road, Kollupitiya, Colombo 03, Sri Lanka.
   - Operating hours (SLST): Monday – Friday 9:00 AM – 6:30 PM, Saturday 9:30 AM – 2:00 PM.
   - Interactive Google Maps embed + 1-click directions link.
6. **🔍 Touch-to-Inspect Picture Deep-Dive (Interactive Lightbox & Case Study Drawer):**
   - **Touch or click ANY showcase picture** to open an interactive modal viewer.
   - **2x Zoom & Drag-to-Pan:** Inspect layout details, typography, and visual assets up close.
   - **Rich Project Story:** Client background, challenge solved, strategy, key metrics (+310% orders, 1.1s speed, 1.4M views), deliverables list, and technology badges.
   - **Instant WhatsApp Action:** 1-Click button with pre-filled message mentioning that exact project.
   - **Keyboard & Touch Gestures:** Arrow keys, Escape key to close, and mobile swipe left/right between projects.
7. **Complete Multi-Page Suite:**
   - `index.html` — Full homepage experience.
   - `services.html` — All 6 detailed packages & service blueprints.
   - `portfolio.html` — 7+ real case studies with interactive picture inspector.
   - `pricing.html` — Real-time interactive scope & cost calculator in LKR/USD.
   - `about.html` — Studio philosophy, team leads, and Colombo 03 workspace gallery.
   - `blog.html` — Insights on Sri Lankan digital trends, PayHere, and mobile SEO.
   - `contact.html` — In-person visit details, driving landmarks, and contact form with WhatsApp dispatch.
   - `404.html` — Custom branded GitHub Pages 404 error page.
8. **100% Secure & Zero API Keys:**
   - No passwords, private tokens, or secret API keys anywhere in the code.
   - Safe to publish on public GitHub repositories!

---

## 🚀 How to Host on GitHub Pages (Step-by-Step)

This repository is pre-configured for GitHub Pages:
- All file paths are strictly relative (`css/style.css`, `images/...`, `js/main.js`).
- `.nojekyll` file is present in the root folder so GitHub Pages doesn't ignore assets.
- `404.html` is ready for custom 404 routing.

### Method 1: Upload via GitHub Web Browser (Easiest)

1. Go to [github.com](https://github.com/) and log in to your GitHub account.
2. Click **New** (green button) or go to `https://github.com/new` to create a new repository:
   - **Repository name:** `webora` (or `webora-website`, or your choice).
   - Set repository to **Public** (required for free GitHub Pages).
   - Leave "Initialize with README" unchecked.
   - Click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Drag and drop **all files and folders inside the `webora` folder**:
   - `index.html`
   - `services.html`
   - `portfolio.html`
   - `pricing.html`
   - `about.html`
   - `blog.html`
   - `contact.html`
   - `404.html`
   - `.nojekyll`
   - `README.md`
   - The `css` folder (`css/style.css`)
   - The `js` folder (`js/main.js`)
   - The `images` folder (all 19+ photos)
5. Type a commit message (e.g. `Initial commit: Webora agency site`) and click **Commit changes**.
6. **Enable GitHub Pages:**
   - Click on the **Settings** tab at the top of your repository.
   - In the left sidebar, click on **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Under **Branch**, select `main` (or `master`) and folder `/(root)`.
   - Click **Save**.
7. Wait 1–2 minutes, then refresh the page. You will see a banner:
   > *Your site is live at `https://<your-username>.github.io/webora/`*

---

### Method 2: Push via Git Terminal / PowerShell

Open PowerShell or Command Prompt in this folder:

```powershell
# 1. Initialize git
git init

# 2. Add all files
git add .

# 3. Commit
git commit -m "Initial launch of Webora Colombo website"

# 4. Rename default branch to main
git branch -M main

# 5. Link your GitHub repository (replace with your repo URL)
git remote add origin https://github.com/<your-username>/webora.git

# 6. Push to GitHub
git push -u origin main
```

Then go to **GitHub Repository** -> **Settings** -> **Pages** -> Select **Branch: `main`** and **Folder: `/ (root)`** -> Click **Save**.

---

## 🌐 Custom Domain (Optional: e.g., `webora.lk`)

If you own `webora.lk` or `webora.com`:
1. In your GitHub repository, go to **Settings** -> **Pages** -> **Custom domain**.
2. Type `webora.lk` and click **Save** (this automatically creates a `CNAME` file).
3. At your domain registrar (e.g., LK Domain Registry, GoDaddy, Cloudflare), add DNS records:
   - **Apex domain A records:**
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **`www` CNAME record:**
     - points to `<your-username>.github.io`
4. Check **Enforce HTTPS** in GitHub Pages settings.

---

## 🛠️ How to Customize Your Details

All details are in plain HTML/JS files:

### 1. Update the WhatsApp Phone Number
Replace `94771234567` with your agency's phone number across:
- `index.html`
- `services.html`
- `portfolio.html`
- `pricing.html`
- `about.html`
- `blog.html`
- `contact.html`
- `404.html`
- `js/main.js` (lines with `agencyNumber = '94771234567'`)

*(Note: In the WhatsApp format `https://wa.me/94771234567`, omit the `+` or leading `0`, and start with Sri Lanka country code `94` followed by 9 digits).*

### 2. Update the Physical Address or Business Hours
Search for `No. 425 Galle Road` in the HTML files and change it to your desired location.

### 3. Update Prices & Service Packages
- Edit the prices in `services.html` and `index.html`.
- To update the real-time Cost Calculator prices, open `pricing.html` and update the `data-price` attributes on the input radio buttons and checkboxes (e.g. `data-price="45000"`).

---

## 📁 Repository File Structure

```text
webora/
├── .nojekyll                 # Bypasses Jekyll on GitHub Pages
├── 404.html                  # Branded 404 error page
├── README.md                 # Complete documentation & GitHub instructions
├── index.html                # Home page with hero, services, why us, visit us, concierge
├── services.html             # Full service catalog & pricing packages
├── portfolio.html            # Case studies & interactive picture inspector
├── pricing.html              # Interactive scope & cost calculator in LKR/USD
├── about.html                # Agency story, team profiles & studio gallery
├── blog.html                 # Digital marketing guides & articles
├── contact.html              # Colombo 03 studio visit, hours, map & contact form
├── css/
│   └── style.css             # Unified responsive stylesheet & modal engine
├── js/
│   └── main.js               # Vanilla JS: Nav, Calculator, Modal, Concierge, Forms
└── images/
    ├── hero.jpg
    ├── colombo-office.jpg
    ├── team.jpg
    ├── web-design.jpg
    ├── social-media.jpg
    ├── branding.jpg
    ├── portfolio-ecommerce.jpg
    ├── portfolio-restaurant.jpg
    ├── portfolio-tech.jpg
    ├── portfolio-travel.jpg
    ├── portfolio-fashion.jpg
    ├── portfolio-realestate.jpg
    ├── portfolio-fitness.jpg
    ├── avatar-1.jpg
    ├── avatar-2.jpg
    ├── avatar-3.jpg
    ├── avatar-4.jpg
    ├── blog-payhere.jpg
    └── blog-social-trends.jpg
```

---

## ⚡ Performance & Quality Highlights

- **Framework-free:** Pure HTML5, CSS3, Vanilla JS. Zero bloat, zero dependencies.
- **Mobile-First:** Tested across mobile screens (360px, 390px, 412px, 768px, 1024px+).
- **Accessible (a11y):** Skip links, high color contrast, semantic landmarks (`header`, `main`, `footer`), ARIA dialog roles, focus management.
- **Security:** Zero private API keys, zero exposed credentials.
- **Offline & CDN friendly:** Fully functional without third-party external CDNs.
