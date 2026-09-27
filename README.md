# Aryan_Portfolio
# ⚡ ARGON — Futuristic Developer Portfolio

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=9b8cff&height=180&section=header&text=ARGON&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />

### `Web Development • Cybersecurity • AI/ML • Software Development`

A futuristic personal portfolio built with **HTML, CSS, JavaScript, SVG animations, and modern web design principles.**

[🌐 Live Portfolio](#) • [💻 GitHub](https://github.com/aaryan2203) • [💼 LinkedIn](https://linkedin.com/in/aaryan2203)

</div>

---

## ✦ About

**ARGON** is a personal developer portfolio designed around a futuristic, minimal, and technology-focused visual identity.

The website presents my work, technical interests, learning journey, and contact information through a dark interface with glowing purple accents and an animated infinity symbol.

> **Build. Learn. Experiment. Repeat.**

The portfolio reflects my interests in:

* 🌐 Web Development
* 🔐 Cybersecurity
* 🤖 Artificial Intelligence & Machine Learning
* 🐍 Python
* ⚙️ C / C++
* 💻 Software Development
* 🚀 Open Source & Experimental Projects

---

## ✨ Features

### ♾️ Animated Infinity Background

The hero section contains a custom SVG infinity symbol with:

* Animated plasma flow
* Gradient lighting
* Glow effects
* Traveling particle/spark
* Smooth animation loop

The infinity design represents **continuous learning, development, and exploration**.

### 🎨 Futuristic UI

The interface uses:

* Dark futuristic theme
* Purple neon accents
* Glassmorphism-inspired elements
* Gradient typography
* Minimal navigation
* Smooth transitions
* Responsive layouts

### 📱 Responsive Design

The portfolio adapts to different screen sizes:

```text
Desktop ────────────────┐
Tablet ─────────────────┤
Mobile ─────────────────┘
```

Mobile-specific adjustments are included for navigation, spacing, and the social dock.

### 🧭 Navigation

The header includes navigation for:

* About
* Work
* Contact

### 🔗 Social Dock

The bottom navigation provides quick access to:

* GitHub
* LinkedIn
* Email
* Instagram

### 🎞️ Scroll Animation

The About section uses `IntersectionObserver` to animate into view when the user scrolls to it.

### ♿ Reduced Motion Support

The website detects:

```javascript
prefers-reduced-motion
```

and reduces/pauses animations for users who prefer reduced motion.

---

# 🛠️ Tech Stack

| Technology           | Purpose                     |
| -------------------- | --------------------------- |
| HTML5                | Page structure              |
| CSS3                 | Styling & responsive design |
| JavaScript           | Interactivity & animations  |
| SVG                  | Infinity animation          |
| Google Fonts         | Typography                  |
| IntersectionObserver | Scroll animations           |

### Fonts

The design uses:

* **Space Grotesk** — Headings
* **Inter** — Body text
* **JetBrains Mono** — Technical/UI elements

---

# 📂 Project Structure

```text
portfolio/
│
├── index.html
│
├── assets/
│   ├── images/
│   └── icons/
│
├── README.md
│
└── LICENSE
```

For a simple deployment, the project can also work as:

```text
portfolio/
└── index.html
```

No framework or build system is required.

---

# 🎨 Design System

### Background

```css
--bg: #0a0912;
--bg-2: #120f1e;
```

### Text

```css
--ink: #f1edff;
--muted: #8d86ad;
```

### Accent

```css
--accent: #9b8cff;
--accent-deep: #5b4fe0;
--accent-glow: #d7cfff;
```

The color palette creates a dark environment with purple/lavender neon highlights.

---

# ♾️ Infinity Animation

The infinity symbol is created entirely with SVG.

The main animation path uses:

```html
<path id="flowPath" ... />
```

A gradient is applied to the path:

```html
<linearGradient id="tubeGrad">
```

and a traveling particle follows the path using:

```html
<animateMotion>
```

JavaScript dynamically calculates the SVG path length:

```javascript
const len = flowPath.getTotalLength();
```

and continuously updates the stroke offset using:

```javascript
requestAnimationFrame(animateFlow);
```

This creates the continuous plasma-flow effect.

---

# 🖥️ Running Locally

Clone the repository:

```bash
git clone https://github.com/aaryan2203/your-portfolio-repository.git
```

Enter the project:

```bash
cd your-portfolio-repository
```

Then open:

```text
index.html
```

in your browser.

### Recommended

Use **VS Code + Live Server**.

1. Open the project in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

---

# 🚀 Deployment

Because this is a static website, it can be deployed using:

* GitHub Pages
* Vercel
* Netlify
* Cloudflare Pages

### GitHub Pages

Push the project to GitHub and enable:

```text
Repository
→ Settings
→ Pages
→ Deploy from branch
→ main
→ /root
```

Your portfolio will then be available through your GitHub Pages domain.

---

# 📸 Preview

Add your portfolio screenshot here:

```markdown
![Portfolio Preview](assets/preview.png)
```

Recommended screenshot:

```text
┌──────────────────────────────────────┐
│              ARGON                   │
│                                      │
│          ♾️ Animated Infinity        │
│                                      │
│        Developer Portfolio           │
│                                      │
│ Web Development • Cybersecurity      │
│          • AI / ML                   │
└──────────────────────────────────────┘
```

---

# 🔐 Security & Privacy

This portfolio is a **static frontend website**.

It does not require:

* A database
* Backend authentication
* Server-side processing
* User accounts
* API keys

External resources currently include Google Fonts and social/contact links.

---

# 🧩 Customization

You can customize the portfolio by editing `index.html`.

### Change Name

```html
<h1>ARGON</h1>
```

### Change Tagline

```html
<p class="tagline">
Your new introduction here...
</p>
```

### Change Social Links

Update the corresponding URLs:

```html
<a href="https://github.com/USERNAME">
```

```html
<a href="https://linkedin.com/in/USERNAME">
```

```html
<a href="https://instagram.com/USERNAME">
```

### Change Colors

Modify the CSS variables:

```css
:root {
    --bg: #0a0912;
    --bg-2: #120f1e;
    --accent: #9b8cff;
    --accent-deep: #5b4fe0;
}
```

---

# 📈 Future Improvements

Planned improvements can include:

* [ ] Interactive project showcase
* [ ] Skills section
* [ ] Experience timeline
* [ ] Project filtering
* [ ] GitHub API integration
* [ ] GitHub contribution graph
* [ ] Animated project cards
* [ ] Cybersecurity projects section
* [ ] AI/ML projects section
* [ ] Contact form
* [ ] Custom cursor
* [ ] Light/dark theme switcher
* [ ] More advanced 3D animations
* [ ] Blog section

---

# 👨‍💻 About Me

I'm a developer focused on **Web Development, Cybersecurity, AI/ML, and Software Development**.

I enjoy learning by building projects and experimenting with new technologies.

My current focus is developing practical projects while expanding my knowledge across software engineering, cybersecurity, and artificial intelligence.

---

# 🌐 Connect

<div align="center">

**GitHub**

https://github.com/aaryan2203

**LinkedIn**

https://linkedin.com/in/aaryan2203

**Instagram**

https://instagram.com/_aaryan2203

</div>

---

# ⭐ Support

If you like this portfolio or find the project useful, consider giving the repository a ⭐.

---

<div align="center">

### `∞ Keep Learning. Keep Building. Keep Exploring. ∞`

**© 2026 ARGON**

</div>
