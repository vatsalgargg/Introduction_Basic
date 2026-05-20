# Vatsal Garg — Cybersecurity Portfolio

> A modern, fully responsive personal portfolio site for a CSE student specialising in Cybersecurity & AI Engineering at BMS College of Engineering.

🔗 **Live:** [vatsalgargg.github.io/Introduction_Basic](https://vatsalgargg.github.io/Introduction_Basic) *(or your deployed URL)*

---

## ⚡ Tech Stack

### Core
| Layer | Technology |
|---|---|
| Markup | **HTML5** — semantic elements (`main`, `section`, `article`, `nav`, `footer`) |
| Styling | **Vanilla CSS3** — custom properties, CSS Grid, Flexbox, `clamp()` fluid type |
| Logic | **Vanilla JavaScript (ES6+)** — no frameworks, no build step |

### Libraries (CDN — zero install)
| Library | Purpose |
|---|---|
| [Lucide Icons](https://lucide.dev) | Crisp SVG icon set replacing emojis |
| [Google Fonts](https://fonts.google.com) | `Outfit` (UI) + `JetBrains Mono` (code/terminal) |

### Design System
| Token | Value |
|---|---|
| Background | `#0d1117` (GitHub dark slate) |
| Accent — Cyan | `#22d3ee` |
| Accent — Blue | `#60a5fa` |
| Accent — Violet | `#a78bfa` |
| Accent — Green | `#34d399` |
| Accent — Amber | `#fbbf24` |
| Font — UI | Outfit 300/400/600/700/800 |
| Font — Mono | JetBrains Mono 400/500/600 |

---

## ✨ Features

- **Two-column hero** — animated typing name + live terminal window showing profile
- **Matrix rain canvas** — subtle animated background (pauses when tab hidden)
- **Scroll progress bar** — gradient progress indicator at top
- **Scroll-reveal animations** — per-card staggered entrance with `IntersectionObserver`
- **Glassmorphism cards** — `backdrop-filter: blur` with coloured border accents
- **Per-skill accent colours** — each of 9 skill cards has its own unique colour identity
- **Hamburger nav** — animated 3-bar → X toggle for mobile
- **Fully responsive** — 6 breakpoints: 360 / 480 / 640 / 768 / 900 / 1100px

---

## 📁 Project Structure

```
Introduction_Basic/
├── index.html      # Single-page app — all sections
├── style.css       # Full design system + responsive styles
└── README.md       # This file
```

---

## 🗂️ Sections

| # | Section | Description |
|---|---|---|
| 1 | **Hero** | Name, subtitle, tech pills, CTA buttons, terminal window |
| 2 | **About** | Bio paragraphs + 4-stat bento grid (ISC2, TryHackMe rank, projects, ML samples) |
| 3 | **Projects** | Soil Sage (AI/ML), InternShield (OSINT/Security), CTF & Pentesting |
| 4 | **Skills** | 9 cards — Cybersecurity, Programming, AI/ML, Databases, Tools, OSINT, Pentesting, Cloud, Core Competencies |
| 5 | **Certifications** | BMSCE degree, ISC2 CC, Bug Bounty Practical |
| 6 | **Contact** | Email, LinkedIn, GitHub, TryHackMe cards |

---

## 🚀 Run Locally

No build tools required — just a static file server:

```bash
# Python (built-in)
python -m http.server 3000

# Node.js (npx)
npx serve .

# VS Code
# Install "Live Server" extension → right-click index.html → Open with Live Server
```

Then open [http://localhost:3000](http://localhost:3000).

---

## 📱 Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| `≤ 1100px` | Tablets landscape |
| `≤ 900px` | Tablets portrait — hero stacks, stats go 4-across |
| `≤ 768px` | Large phones — hamburger nav, all grids single column |
| `≤ 640px` | Mid phones — buttons grid, terminal compact |
| `≤ 480px` | Small phones (iPhone SE) — single-column buttons, minimal terminal |
| `≤ 360px` | Very small phones — typography scales down |

---

## 👤 Author

**Vatsal Garg** — CSE @ BMS College of Engineering, Bengaluru  
[LinkedIn](https://www.linkedin.com/in/vatsal-gargg) · [GitHub](https://github.com/vatsalgargg) · [TryHackMe](https://tryhackme.com/p/mrR0bOt) · [Email](mailto:vatsalg80@gmail.com)

---

*Built with pure HTML, CSS & JS — no frameworks, no dependencies, no build step.*
