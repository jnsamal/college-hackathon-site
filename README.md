# AVC HackFusion 2.0 – Inter-College Hackathon Website

A modern, fully responsive landing page for the **AVC HackFusion 2.0** inter-college hackathon, hosted at the AVC Institute premises. The site features a glass morphism aesthetic, smooth animations, and clear presentation of event rules, prizes, schedule, and registration call-to-action.

![Screenshot](screenshot.png) <!-- You can replace with an actual screenshot -->

---

## ✨ Features

- **Glass Morphism Design** – Frosted glass cards, transparent navigation, and layered backgrounds create a futuristic look.
- **Animated Gradient Background** – Moving semi-transparent orbs that react dynamically.
- **Sections**
  - Hero with key stats (48 hours, 2 days, free entry, all colleges)
  - About the hackathon & AVC Institute
  - Rules & Guidelines (highlighted “No AI” policy)
  - Prizes (winner freebies + universal participation certificate)
  - Two-day detailed schedule
  - CTA (Registration button with interactive alert)
  - Footer
- **Responsive & Mobile-Friendly** – Collapsible hamburger menu, stacked grids, and scalable typography.
- **Smooth Scrolling Navigation** – Sticky navbar with active state.
- **No Backend Required** – Pure frontend built with React (via CDN) and plain CSS.

---

## 🎨 Color Palette

| Color         | Hex       | Usage                  |
|---------------|-----------|------------------------|
| Lavender      | `#D3D3FF` | Accent text, borders   |
| Violet        | `#9400D3` | Buttons, gradients     |
| Thistle       | `#D8BFD8` | Background orbs, text  |
| Pink          | `#ED80E9` | Highlights, “No AI” badge |

---

## 🛠️ Tech Stack

- **React 18** (loaded via CDN)
- **Babel Standalone** – for JSX transpilation in the browser
- **HTML5 & CSS3** – Custom styles, CSS Grid, Flexbox, animations
- **No external CSS frameworks** (pure custom design)

---


The entire application is self-contained inside `index.html`. There are no separate JS files or build tools required.

---

## 🚀 How to Run Locally

1. **Clone or download** the repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. That’s it! The website will render immediately.

> **Note:** An internet connection is required on the first load to fetch React and Babel from CDN. After that, everything runs locally in the browser.

---

## 🌐 Deployment

Because the project is a single static HTML file, you can host it on any static server or platform:

- **GitHub Pages** – Push the file to a `docs/` folder or root and enable Pages.
- **Netlify / Vercel** – Drag and drop `index.html`.
- **Any shared hosting** – Simply upload the file.

---

## 📋 Key Rules & Guidelines Displayed

- Teams of 2–4 from recognized colleges.
- 2-day in-person event at AVC Institute.
- **Strictly NO AI tools allowed** (ChatGPT, Copilot, etc.) – prominently highlighted.
- All work must be original and built during the hackathon.
- Mandatory final presentation and code of conduct.

---

## 🏆 Prizes

- **Winning team receives:**
  - Branded backpack
  - Hackathon cap
  - Insulated water bottle
- **All participants receive:** Official AVC Institute participation certificate.

---

## 📅 Event Schedule

| Day 1 (July 15)              | Day 2 (July 16)              |
|------------------------------|------------------------------|
| Registration & opening       | Breakfast                    |
| Hackathon begins             | Submission deadline          |
| Lunch, mentor rounds         | Lunch, final presentations   |
| Overnight coding             | Judging & award ceremony     |

---

## ⚙️ Customization

You can easily modify:

- **Dates & times** – Update in the `Hero`, `Rules`, and `Timeline` components.
- **Email / contact info** – Change in the CTA section and footer.
- **Registration link** – Replace the `alert()` with an actual form URL in the `CTA` component.
- **Colors** – Edit the CSS `:root` variables at the top of the `<style>` block.

---

## 📝 License

This project is intended for educational and promotional use by AVC Institute. You are free to adapt it for your own college events with appropriate attribution.

---

**Built with ❤️ for the student developer community – without using AI! 😉**
