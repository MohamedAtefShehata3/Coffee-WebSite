<div align="center">

# ☕ Cold Coffee — Landing Page

### A modern, responsive and animated coffee shop website

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Swiper.js-6332F6?style=for-the-badge&logo=swiper&logoColor=white" alt="Swiper" />
</p>

<p>
  <img src="https://img.shields.io/badge/Responsive-Yes-success?style=flat-square" alt="Responsive" />
  <img src="https://img.shields.io/badge/Dependencies-Zero%20Build-blue?style=flat-square" alt="No build" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square" alt="License" />
</p>

[🌐 Live Demo]([https://mohamedatefshehata3.github.io/Coffee-WebSite/]) • [🐞 Report Bug](https://github.com/MohamedAtefShehata3/https://github.com/MohamedAtefShehata3/Coffee-WebSite.git/issues) • [✨ Request Feature](https://github.com/YOUR-USERNAME/YOUR-REPO/issues)

</div>

---

## 📖 About The Project

**Cold Coffee** is a polished single-page landing website for a coffee shop. It combines a bold visual identity with smooth scroll animations, an interactive product carousel and a fully responsive layout that looks great on every screen — from small phones to large desktops.

Built with pure **HTML, CSS and Vanilla JavaScript**, so there is no build step and nothing to install.

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🎠 | **Popular Carousel** | Touch-friendly, looping, centered slider powered by Swiper.js |
| 🎬 | **Scroll Animations** | Staggered, cinematic reveal effects using ScrollReveal |
| 📱 | **Fully Responsive** | Mobile-first design with breakpoints for tablets and desktops |
| 🍔 | **Slide-in Mobile Menu** | Toggle open/close menu that auto-closes when a link is clicked |
| 🧭 | **Active Section Highlight** | Navigation link updates automatically while you scroll |
| 🌫️ | **Shadow Header** | Header gets a subtle shadow once the page is scrolled |
| ⬆️ | **Scroll-Up Button** | Appears after scrolling down for quick return to top |
| 🛍️ | **Product Showcase** | Grid of the most requested drinks with prices and add buttons |
| 📬 | **Contact Section** | Email, location, delivery info and a clear notice block |
| 💳 | **Rich Footer** | Social links, payment methods and a newsletter subscription form |

---

## 🛠️ Built With

- **HTML5** — semantic structure
- **CSS3** — custom properties (variables), Flexbox, Grid, media queries
- **JavaScript (ES6)** — DOM manipulation and scroll logic
- [**Swiper.js**](https://swiperjs.com/) — carousel / slider
- [**ScrollReveal**](https://scrollrevealjs.org/) — scroll-triggered animations
- [**Remix Icon**](https://remixicon.com/) — icon set

---

## 📂 Project Structure

```bash
cold-coffee/
├── index.html
├── assets/
│   ├── css/
│   │   ├── styles.css
│   │   └── swiper-bundle.min.css
│   ├── js/
│   │   ├── main.js
│   │   ├── scrollreveal.min.js
│   │   └── swiper-bundle.min.js
│   └── img/
│       └── ...                # coffee, beans, ice, leaves, cards, favicon
└── README.md
```

---

## 🚀 Getting Started

No installation or build tools required.

### 1. Clone the repository

```bash
git clone https://github.com/MohamedAtefShehata3/YOUR-REPO.git
```

### 2. Open the project

```bash
cd https://github.com/MohamedAtefShehata3/Coffee-WebSite.git
```

### 3. Run it

Just open `index.html` in your browser, **or** use a local server such as the VS Code **Live Server** extension:

```bash
# Optional – using npx
npx serve .
```

---

## 🧠 How It Works

<details>
<summary><b>Click to expand the JavaScript highlights</b></summary>

<br/>

- **Menu toggle** — adds/removes the `show-menu` class on the nav element.
- **Shadow header** — listens to `scroll` and toggles `shadow-header` after 50px.
- **Scroll-up button** — shows after 350px of scrolling.
- **Active link** — loops through every `section[id]` and highlights the matching nav link based on the current scroll position.
- **Swiper** — `loop`, `grabCursor`, `slidesPerView: 'auto'` and `centeredSlides` with a wider gap on large screens.
- **ScrollReveal** — global defaults (`origin: top`, `distance: 60px`, `duration: 2000`) with custom delays per element for a layered intro.

</details>

---

## 🎨 Customization

All colors, fonts and sizes live in `:root` inside `styles.css`:

```css
:root {
  /* Change these to re-theme the whole site */
  --first-color: ...;
  --title-color: ...;
  --text-color: ...;
  --body-color: ...;
}
```

Replace the images in `assets/img/` and edit the text in `index.html` to make the site your own.

---

## 🗺️ Roadmap

- [x] Responsive layout
- [x] Carousel & scroll animations
- [x] Mobile menu
- [ ] Dark / light theme toggle
- [ ] Working newsletter form
- [ ] Shopping cart functionality
- [ ] Multi-language support (EN / AR)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create your branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m "Add AmazingFeature"`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 👨‍💻 Author

**Mohamed**

Full Stack Web Developer · Computer Science Student @ EELU

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR-USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-PROFILE)

---

<div align="center">

⭐ **If you like this project, give it a star!** ⭐

Made with ☕ and ❤️ in Egypt

</div>
