# SpeedCheck // Web PageSpeed Insights Analyzer

A clean, modern, and lightweight **Google PageSpeed Insights** performance analyzer built with pure HTML5, Tailwind CSS, and vanilla JavaScript. 

Audits any live website URL for both **Mobile** and **Desktop** environments using the official Google PageSpeed Insights API (Lighthouse v11+ engine).

---

## ✨ Features

- 🌟 **Modern Light Theme:** Designed after Google's Material / PageSpeed Insights interface with clean white surfaces, accessible typography (`Inter`), and responsive cards.
- 🎯 **All 4 Lighthouse Categories:**
  - **Performance** (Score 0-100)
  - **Accessibility** (Score 0-100)
  - **Best Practices** (Score 0-100)
  - **SEO** (Score 0-100)
- ⚡ **Core Web Vitals & Diagnostics Metrics:**
  - **FCP** (First Contentful Paint)
  - **LCP** (Largest Contentful Paint)
  - **TBT** (Total Blocking Time)
  - **CLS** (Cumulative Layout Shift)
  - **Speed Index**
  - **TTI** (Time to Interactive)
- 📸 **Captured Page Snapshot:** Renders the actual screenshot captured by Lighthouse during the simulated audit.
- 💡 **Opportunities (Load Time Savings):** Identifies performance bottlenecks (e.g. render-blocking resources, unoptimized images, unused JS/CSS) with exact estimated time and byte savings, expandable resource tables.
- 🛠️ **Technical Diagnostics:** Deep-dive into DOM size, cache policies, font-display, main-thread work, etc.
- ✅ **Passed Audits:** Collapsible section displaying all passing checks.
- 📱 / 💻 **Mobile & Desktop Switching:** Runs audits in parallel and switches strategies instantly with zero reload delay.
- 🖨️ **Print & PDF Export:** Clean print stylesheet to easily save or share PDF reports.

---

## 🚦 Score Interpretation Scale

| Score | Rating | Color Indicator |
| :--- | :--- | :--- |
| **90 – 100** | Good / Pass | 🟢 Emerald Green (Circle) |
| **50 – 89** | Needs Improvement | 🟡 Amber / Orange (Square) |
| **0 – 49** | Poor | 🔴 Red (Triangle) |

---

## 🚀 Quick Start / Local Usage

No build tools or Node server required! Simply open `index.html` in any modern web browser:

```bash
# Clone the repository
git clone https://github.com/zhsaikot/web-speedcheck-zhs.git

# Open index.html directly or serve with any static server:
npx serve .
# or
python -m http.server 8000
```

---

## 🛠️ Tech Stack

- **Markup & Styling:** HTML5, [Tailwind CSS](https://tailwindcss.com) (CDN), [Inter Font](https://fonts.google.com/specimen/Inter)
- **Engine:** [Google PageSpeed Insights API v5](https://developers.google.com/speed/docs/insights/v5/get-started) (Lighthouse)
- **Runtime:** Vanilla JavaScript (ES6+), 100% Client-Side

---

## 👨‍💻 Author

Developed by **Md. Ziaul Hasan**  
- GitHub: [@zhsaikot](https://github.com/zhsaikot)