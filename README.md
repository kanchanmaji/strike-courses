# 🎓 STRIKE — Modern Course Selling Website

A **premium-looking static website** for selling online courses — built only with **HTML5 + CSS3**, completely **JavaScript-free**.  
It includes sections for free and paid courses, instructor showcase, and responsive design optimized for all devices.

---

## ✨ Features

✅ **Clean, Premium UI**
- Minimalistic glass-morphism & gradient design.
- Fully responsive for mobile, tablet, and desktop.

✅ **Free + Paid Course System**
- Separate sections for free and paid courses.
- Each course card includes image, title, instructor, and CTA buttons.

✅ **Instructor Profiles**
- Stylish instructor cards with background overlays and subtle hover animations.

✅ **3D Preview Section**
- Static 3D-like cards using only CSS transforms (no JS).

✅ **Logo + Branding**
- Gradient or image-based logo mark.
- Bold logo text with first-letter highlight.

✅ **Static Yet Dynamic-Feel**
- Animations and depth effects achieved purely via CSS.

---

## 📂 Project Structure

```
STRIKE/
│
├── index.html              # Main homepage
├── /assets
│   ├── logo.png            # Website logo
│   ├── mern.jpg            # Example course image
│   ├── earth.jpg           # Background 3D preview image
│   ├── instructor1.jpg     # Instructor photo samples
│   └── ...                 # Add more course/instructor images
└── /styles
    └── style.css           # All CSS styling
```

---

## 🖌️ Customization Guide

### 🎨 Change Theme Colors
Open `style.css and style1.css` and modify:

```css
:root {
  --accent: #FFD700;
  --accent2: #FF9900;
  --bg: #0a0a0a;
  --text: #ffffff;
}
```

### 🧑‍🏫 Add New Courses
Duplicate one of the course cards in `index.html`:

```html
<div class="course-card paid">
  <div class="card-image" style="background: url('assets/react.jpg') center/cover no-repeat;"></div>
  <h3>React Mastery</h3>
  <p>Build modern UI with React step-by-step.</p>
  <button class="btn btn-accent">Buy Now</button>
</div>
```

---

## 💡 Tech Stack

- **HTML5** — Semantic markup  
- **CSS3** — Flexbox, Grid, 3D Transforms, Gradients, Shadows  
- **No JavaScript or frameworks** — 100% static  

---

## 🚀 Deployment

You can host it anywhere:
- **GitHub Pages**
- **Netlify**
- **Vercel**
- **Firebase Hosting**

Just drag and drop the project folder or push via Git.

---

## 📸 Preview

![Preview Screenshot](assets/preview.jpg)

*(Add your website screenshot as `preview.jpg` in the assets folder)*

---

## 🧑‍💻 Author

**Kanchan Maji**  
Full-stack Developer & Tech Enthusiast  
[GitHub](https://github.com/kanchanmaji) • [LinkedIn](#)

---

## 🛡️ License

This project is licensed under the **MIT License** — feel free to use and modify with credit.

---

## ❤️ Contributions

Pull requests, improvements, and design ideas are welcome!  
If you find any issues, please open a new **Issue** on GitHub.

---
