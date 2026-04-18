# HelpHub AI 🤝

**A community-powered help network for students, mentors, creators, and builders.**  
Built for SMIT Grand Coding Night 2026 — a multi-page frontend product with AI-powered request intelligence, community trust scores, and a real platform feel.

---

## 🔗 Live Demo

> Open `https://helphub-ai-01.netlify.app/` in your browser — no server, no install, no setup.

---

## 🧠 What is HelpHub AI?

HelpHub AI is a premium-feel web platform where people can **ask for help**, **offer help**, and **track real community impact** — all surfaced by AI intelligence that matches the right people to the right problems.

It's not a form. It's an ecosystem.

---

## 📸 Screens

| Screen | Description |
|---|---|
| **Landing** | Hero, core flow, featured requests, live stats |
| **Login** | Role-based demo identity + community access |
| **Dashboard** | Personal stats, active requests, recent activity |
| **Explore / Feed** | Filterable community help requests |
| **Request Detail** | AI summary, helpers list, trust scores, actions |
| **Create Request** | AI-guided form with urgency detection + rewrite suggestions |
| **Messages** | Direct communication between helpers and requesters |
| **AI Center** | Platform intelligence — trends, urgency signals, recommendations |
| **Leaderboard** | Top contributors ranked by trust score |
| **Notifications** | Real-time community updates |

---

## ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 (semantic) |
| Styling | CSS3 — custom properties, grid, flexbox |
| Logic | Vanilla JavaScript |
| Fonts | [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts |
| Storage | LocalStorage (demo session persistence) |
| Backend | None — fully frontend |
| Build Tools | None — zero dependencies |

---

## 🗂️ Project Structure

```
helphub/
├── css/
│   └── global.css          # Shared design system — variables, nav, cards, chips, buttons, forms
├── js/
│   └── nav.js              # Shared navigation active-state logic
├── index.html              # Landing page
├── login.html              # Login / Signup
├── dashboard.html          # User dashboard
├── explore.html            # Explore feed with filters
├── detail.html             # Request detail view
├── create.html             # Create a new help request
├── messages.html           # Direct messaging
├── ai-center.html          # AI intelligence center
├── leaderboard.html        # Community leaderboard
└── notifications.html      # Notification feed
```

---

## ✨ Key Features

- **AI Request Intelligence** — Auto-categorization, urgency detection, tag suggestions, and description rewrites
- **Community Trust Graph** — Helper rankings, trust score percentages, and contribution history
- **Filterable Explore Feed** — Browse by category, urgency, skill, and location
- **Role-Based Access** — Need Help, Can Help, or Both
- **Direct Messaging** — Helpers and requesters communicate in-thread
- **AI Center Dashboard** — Platform-wide trend pulse, urgency watch, and mentor pool stats
- **Leaderboard** — Recognizes top contributors publicly
- **Zero Dependencies** — Pure HTML, CSS, and JavaScript. Opens straight from the file system.

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/helphub-ai.git

# Open in browser
cd helphub-ai
open index.html
```

No npm. No build step. No configuration. Just open and go.

---

## 🎨 Design System

The UI is built on a custom design system defined in `css/global.css`:

```css
--bg:        #f0ede6   /* warm off-white page background */
--dark:      #1e2b27   /* deep forest green for hero panels + nav */
--teal:      #1a7a5e   /* primary brand color */
--teal-btn:  #1a8a68   /* CTA button green */
--border:    #e5e0d8   /* soft warm border */
--tag-bg:    #f5f2ec   /* chip / tag backgrounds */
```

**Typography:**
- `Syne` — headings, eyebrows, stats (bold, high character)
- `DM Sans` — body, labels, inputs (clean, readable)

**Layout:**
- CSS Grid for page layouts
- Flexbox for component internals
- CSS custom properties for consistent theming across all 10 pages

---

## 👥 Team

Built with 💚 for **SMIT Grand Coding Night 2026**

---

## 📄 License

MIT — free to use, modify, and build on.
