# ABC Hotel — Premium Static Hotel Website

A modern, responsive, static hotel website built as a portfolio/demo project by **Ixoria Pixel**. Designed to show hotel owners how their property could be presented online — clean, premium, and enquiry-focused (no booking engine, no payments, no backend).

**Live demo:** _add your Netlify URL here after deploying_

---

## ✨ Features

- Sticky header — transparent over the hero, solid on scroll
- Full-screen cinematic hero section
- About, Rooms & Suites, Facilities, Dining, Nearby Attractions sections
- Filterable photo gallery (Exterior, Reception, Lobby, Rooms, Bathrooms, Restaurant, Pool, Garden & Terrace, Parking) with a lightbox (previous/next, keyboard support)
- Guest reviews carousel (swipeable on mobile)
- Accordion-style Hotel Policies section
- Location section with an embedded map
- Floating WhatsApp button with a pre-filled enquiry message
- Fully responsive: mobile, tablet, laptop, desktop
- No frameworks — plain HTML5, CSS3, and vanilla JavaScript
- Lazy-loaded images, lightweight animations, semantic HTML, basic SEO/Open Graph tags

---

## 🗂 Project Structure

```
abc-hotel/
├── index.html    # Everything — markup, CSS (in <style>), and JS (in <script>)
└── README.md
```

This is a single self-contained HTML file — CSS and JavaScript are inlined, so there's nothing else to host or link. Just upload `index.html` anywhere.

---

## 🛠 Tech Stack

- HTML5
- CSS3 (custom properties, Grid, Flexbox — no framework)
- Vanilla JavaScript (no libraries)
- Google Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) + [Manrope](https://fonts.google.com/specimen/Manrope)
- Demo imagery from [Unsplash](https://unsplash.com)

---

## ▶️ Run Locally

No build step or dependencies required.

**Option A — just open it**
Double-click `index.html`, or right-click → Open with your browser.

**Option B — local server (recommended, avoids any relative-path quirks)**
```bash
# Python 3
python3 -m http.server 8000

# or Node.js
npx serve .
```
Then visit `http://localhost:8000`.

---

## 📝 Before Using This as a Real Client Site

This is demo content. Replace the following before handing it off:

- [ ] Hotel photos — swap Unsplash URLs in `index.html` for the real property's photos (search `<img src=` and `background`)
- [ ] Phone number, email, and address (footer, contact cards, WhatsApp links)
- [ ] WhatsApp number in the two `wa.me/910000000000...` links
- [ ] Google Maps embed URL in the Location section
- [ ] Hotel Policies text (clearly marked as demo content in the file)
- [ ] Social media links (Facebook, Instagram) in the footer
- [ ] Favicon and Open Graph image

---

## 📤 Deploy

See the step-by-step guide below for pushing this to GitHub and deploying it on Netlify.

---

## Credits

Website by **Ixoria Pixel**.
