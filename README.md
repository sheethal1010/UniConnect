# UniConnect — UX Wireframe Specification

> Low-fidelity wireframe design specification for a unified campus collaboration platform.

🔗 **[View Live →](https://your-username.github.io/your-repo-name)**

---

## About

UniConnect is a campus platform concept that connects students across five workflows:

- 📚 **Study Partner Matching** — Find partners by course, availability, and learning style
- 🤝 **Project Team Formation** — Post and join capstone/hackathon teams by skill
- 💼 **Freelance Marketplace** — Post and bid on micro-tasks between students
- 📦 **Resource Sharing** — Upload and borrow notes, textbooks, and equipment
- 📍 **Study Space Booking** — Real-time campus room availability and reservations

This repo contains a complete **UX wireframe specification** — 14 screens, fully documented.

---

## What's Inside

| File | Description |
|------|-------------|
| `index.html` | Complete interactive wireframe specification (single file, no dependencies) |
| `README.md` | This file |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing |

---

## Screens Documented

| ID | Screen | Type |
|----|--------|------|
| S01 | Landing Page | Public |
| S02a | Login | Auth |
| S02b | Sign Up | Auth |
| S03 | Profile Creation (3-step onboarding) | Onboarding |
| S04 | Dashboard | Core |
| S05 | Study Partner Matching | Feature |
| S06 | Project Team Formation | Feature |
| S07 | Freelance Marketplace | Feature |
| S08 | Resource Sharing | Feature |
| S09 | Study Space Booking | Feature |
| S10 | Notifications & Messages | Global |
| S11 | User Profile | Profile |
| S12 | Admin Panel | Admin |
| S13–14 | Edge Cases & Error States | States |

Each screen includes:
- ASCII layout diagram (Figma-recreatable)
- Full UI component list
- All user interactions (trigger → action)
- Navigation flow map
- Edge cases (empty, error, offline)

---

## How to Use

### View Online (GitHub Pages)
Visit the live link at the top of this README.

### Run Locally
No build step needed. Just open `index.html` in any browser:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
open index.html   # macOS
# or
start index.html  # Windows
```

### Keyboard Shortcuts
When viewing wireframes, use **← →** arrow keys to navigate between screens.

---

## Hosting on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set Source to **Deploy from a branch**
4. Select branch: `main`, folder: `/ (root)`
5. Click **Save** — your site will be live in ~60 seconds

---

## Tech Stack

- Pure HTML, CSS, JavaScript — zero dependencies, zero build tools
- Google Fonts: DM Mono, Fraunces, DM Sans (loaded via CDN)
- Works offline after first load (fonts cached by browser)

---

## License

MIT — free to use, adapt, and build upon.
