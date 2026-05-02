# 🏮 Himalayan Thangka Gallery

A modern, responsive website celebrating sacred Himalayan Thangka artwork. Built with pure HTML, CSS, and vanilla JavaScript — featuring gallery browsing, pagination, customer reviews, and comprehensive FAQ.

---

## ✨ Features

### 🎨 **Gallery**
- 24+ authentic Thangka artworks with filtering by category
- Multiple filter categories: Compassion, Wisdom, Protection, Enlightenment, Abundance, Longevity, Mandala
- Sorting options: Date, Name, Category
- Grid and List view modes
- **Pagination system** - 12 images per page with Previous/Next navigation
- Interactive lightbox modal for detailed artwork viewing
- SVG placeholder artwork cards

### ⭐ **Reviews & Testimonials**
- 9 verified customer reviews from collectors worldwide
- Infinite carousel on homepage (60s seamless loop animation)
- Dedicated reviews page with **6 reviews per page pagination**
- Star ratings, location tags, and customer origins

### ❓ **FAQ**
- Comprehensive knowledge base with 4 main categories:
  - About Thangkas
  - Sourcing & Authenticity
  - Care & Preservation
  - Contact & Support
- Expandable accordion UI with smooth animations

### 🎯 **Design & UX**
- **Responsive Design** - Mobile-first approach (works on all devices)
- **Color Palette:** Gold (#d4951a), Ember (#b84a0c), Ink (#180800), Parchment (#faf5ec)
- **Typography:** Cinzel (headers), EB Garamond (body)
- Fixed navigation with smooth scrolling
- Shimmer gradient footer animation
- Smooth page transitions

---

## 📁 Project Structure

```
thangka-gallery/
├── index.html          # Homepage
├── gallery.html        # Full gallery (12 items/page)
├── reviews.html        # Testimonials (6 items/page)
├── faq.html           # FAQ accordion
├── data/
│   └── artworks.js    # 24 artwork database
├── css/               # Stylesheets folder
├── js/                # JavaScript modules folder
├── images/            # Image assets
└── README.md          # This file
```

---

## 🚀 Getting Started

### Installation

```bash
# Clone repository
git clone https://github.com/MEELAN2001/thangka-gallery.git
cd thangka-gallery

# Open locally
# Windows: Double-click index.html
# Or start a local server:
python -m http.server 8000
# Visit: http://localhost:8000
```

### Deploy
- **Netlify:** Drag & drop folder to [netlify.com](https://netlify.com)
- **GitHub Pages:** Enable in repository settings
- **Vercel:** Connect GitHub repo at [vercel.com](https://vercel.com)

---

## 💻 Technologies

- **HTML5** - Semantic markup
- **CSS3** - Responsive design, animations, gradients
- **JavaScript (Vanilla)** - Pagination, accordion, interactions
- **No Dependencies** - Zero build tools or frameworks

---

## 📱 Key Features

### Pagination
- **Gallery:** 12 items per page (2 pages total)
- **Reviews:** 6 items per page (2 pages total)
- Smooth scroll to top on page change
- Previous/Next/Page Number navigation

### Responsive Breakpoints
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

### Animations
- Rotating dharma wheel (14s spin)
- Shimmer footer gradient (4s loop)
- Testimonials carousel (60s infinite)
- Staggered card animations

---

## 📸 Screenshots

Create a `screenshots/` folder in your repository and add:

```
screenshots/
├── homepage-hero.png
├── gallery-pagination.png
├── reviews-page.png
└── faq-accordion.png
```

See "Adding Screenshots" section below ↓

---

## 📝 How to Add Screenshots to GitHub

### Step 1: Create Screenshots Folder

```bash
mkdir screenshots
```

### Step 2: Take Screenshots

**Windows:**
- Press `Print Screen` or `Win + Shift + S`
- Paste into Paint/Photoshop
- Save as PNG in `screenshots/` folder

**Mac:**
- Press `Cmd + Shift + 4` → Select area → Auto-saves to Desktop
- Move to `screenshots/` folder

**Linux:**
- Use `gnome-screenshot` or similar tool
- Save as PNG in `screenshots/` folder

### Step 3: Commit & Push

```bash
git add screenshots/
git commit -m "Add project screenshots to documentation"
git push origin main
```

### Step 4: Reference in README

In your README.md, add:
```markdown
## 📸 Screenshots

### Homepage
![Homepage Hero](./screenshots/homepage-hero.png)

### Gallery
![Gallery with Pagination](./screenshots/gallery-pagination.png)

### Reviews Page
![Reviews Page](./screenshots/reviews-page.png)

### FAQ
![FAQ Accordion](./screenshots/faq-accordion.png)
```

---

## 📊 Artworks Database

24 authentic Thangka artworks with:
- ID, name, category, tags
- Medium, size, artist, origin
- Detailed descriptions
- SVG placeholder graphics

---

## 🌐 Browser Support

✅ Chrome, Firefox, Safari, Edge (Latest)  
❌ Internet Explorer

---

## 📄 License

MIT License - Open source and free to use

---

## 👤 Author

**MEELAN** - Himalayan Thangka Gallery  
📧 Email: info@thangka.com  
🌍 Based in: Kathmandu, Nepal  
🔗 GitHub: [@MEELAN2001](https://github.com/MEELAN2001)

---

## 🙏 Acknowledgments

Dedicated to the preservation of Himalayan Buddhist art tradition and the master artists of Nepal, Tibet, and Bhutan.

---

**Crafted with devotion · Kathmandu** ☸
