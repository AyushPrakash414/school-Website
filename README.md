# St. Thomas' School, Gyanpur — Official Website

A responsive, animated school website built with modern HTML5, CSS3 animations, and vanilla JavaScript.

* **School Name:** St. Thomas' School, Gyanpur
* **Established:** 1988 (Over 38 years of academic excellence)
* **School Motto:** *"Love One Another"*
* **Student Leadership Motto:** *"Leadership · Responsibility · Service"*
* **Four Houses:** Red House, Blue House, Green House, Yellow House (inspired by the quadrants of the school crest)

---

## Pages
- `index.html` — Home page with hero, St. Thomas' crest, sports day march past photo, floating badges, marquee ticker, school pillars, statistics, and highlights.
- `gallery.html` — Interactive photo and video gallery featuring all authentic assets with category filter tabs and an animated lightbox modal viewer.
- `students.html` — Student Cabinet directory for **Session 2026-27** featuring Head Boy Aryan Shukla, Head Girl Arushi Mishra, Red/Blue/Green/Yellow House Captains & Vice-Captains, and Sports Captains.
- `staff.html` — Leadership & Educators directory featuring the Principal's address photo and the dedicated faculty team photo.
- `classes.html` — Academic curriculum pathways (Primary Wing I–V, Middle School VI–VIII, Secondary IX–X, and Senior Secondary XI–XII Science/Commerce) along with co-curricular crafts and Rangoli arts.

---

## Integrated Assets in `assets/`
* `logo.png` / `images.jpg` — Official school crest and shield logo.
* `images (1).jpg` — Annual Sports Day March Past with students holding the official blue school flag.
* `WhatsApp_Image_2023-06-30_at_10.18.55.jpeg` — Official Investiture Ceremony stage group photo.
* `images (2).jpg` — Official Student Cabinet Session 2026-27 roster.
* `774727018_1046843444981224_6042588518703513516_n.jpg` — Principal / Director addressing students at the official podium on Independence Day.
* `774388943_1046846474980921_3267701753392202746_n.jpg` — Student patriotic speech at the podium.
* `images (3).jpg` — Inter-house floral Rangoli competition (swan-and-lotus petal art).
* `images (4).jpg` — Primary / Middle school creative craft workshop.
* `839874103_1095808553418046_1845739914169268052_n.jpg` — Dedicated faculty members on campus.

---

## Animation & Responsiveness Features
- **Keyframe Animations:**
  - `@keyframes dropIn` for smooth navbar slide-down.
  - `@keyframes riseIn` for staggered entrance reveals across cards.
  - `@keyframes photoFloat` and `@keyframes float` for floating hero visuals and stat chips.
  - `@keyframes pulse` for glowing notification dots.
  - `@keyframes spin` for celestial sparkle accents.
  - `@keyframes blobMove` for organic background ambiance.
  - `@keyframes marquee` for smooth continuous ticker scroll.
- **Micro-Interactions & Hover:**
  - Logo rotates with spring easing on hover.
  - 3D card tilt, image zoom (`scale(1.1)`), and gradient overlay sliding.
  - Buttons with tactile translateY lift and deep shadow glow.
- **Interactive Lightbox Modal in `gallery.html`:**
  - Dynamic category filtering (`All`, `Sports & Parade`, `Student Leadership`, `Events & Celebrations`, `Arts & Creativity`).
  - Animated full-screen photo viewer with keyboard ESC support and background dismiss.
- **Responsive Layout:**
  - Multi-tier `@media` queries covering desktop (1200px+), tablet (768px - 960px), and mobile (under 460px).
  - Mobile hamburger drawer navigation with animated reveal.
  - `prefers-reduced-motion` compliance for accessibility.

---

## Run Locally
1. Open the folder in VS Code.
2. Open `index.html` in your browser (or use the VS Code Live Server extension).
3. Browse between pages using the top navigation bar.
