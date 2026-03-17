
# 📚 System Design Study Tracker

A self-contained, interactive **6-week study planner** for learning system design — built as a single HTML file with zero dependencies.

Combines the two best free system design resources on GitHub into one structured, daily to-do tracker with persistent progress, streaks, and a clean UI.

---

## 🗂️ Resources Used

| Repo | Why |
|------|-----|
| [karanpratapsingh/system-design](https://github.com/karanpratapsingh/system-design) | Clean, beginner-friendly prose — used as the primary reading source for Weeks 1–4 |
| [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) | Worked design walkthroughs, Anki decks, and estimation practice — used for Weeks 5–6 |

---

## ✨ Features

- **6-week hybrid study plan** — organic progression from fundamentals to mock interviews
- **Daily to-do checklist** — 4 tasks per day, each mapped to a specific section of the source repos
- **Persistent progress** — checkboxes save to `localStorage`, so your progress survives browser refreshes
- **Day streak counter** — tracks consecutive fully-completed days
- **Source tagging** — every day is colour-coded by which repo to use (or both)
- **Zero dependencies** — single `.html` file, works fully offline

---

## 📅 What's Covered

| Week | Theme | Primary Source |
|------|-------|---------------|
| 1 | Networking & core foundations | karanpratapsingh |
| 2 | Databases — SQL, NoSQL, CAP, replication | karanpratapsingh |
| 3 | Async, messaging & communication protocols | Both |
| 4 | Advanced patterns — consistent hashing, sagas, CQRS | karanpratapsingh |
| 5 | Design walkthroughs — Pastebin, Twitter, URL shortener | donnemartin |
| 6 | Mock interviews & personal cheatsheet | Both |

---

## 🚀 Getting Started

No install. No build step. No npm.

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/system-design-tracker.git

# Open the tracker
open system_design_6week_tracker.html
```

Or just [download the HTML file](./system_design_6week_tracker.html) and open it in any browser.

---

## 🛣️ Roadmap

This project is actively being extended. Planned features:

- [ ] **Custom planner mode** — let users input their own topics, resources, and timeframes
- [ ] **Export progress** — download your completed cheatsheet as PDF
- [ ] **Shareable plans** — generate a URL to share your study plan with others
- [ ] **Multiple tracks** — add tracks for frontend, backend, ML system design
- [ ] **Timer mode** — 45-minute mock interview countdown per design session
- [ ] **Notes per day** — add your own reflections inline

> Want a feature? Open an [issue](../../issues) or submit a PR — contributions welcome.

---

## 🤝 Contributing

1. Fork the repo
2. Make your changes in `system_design_6week_tracker.html`
3. Open a pull request with a clear description of what you changed and why

---

## 📄 License

MIT — free to use, fork, and build on.

---

## 🙏 Credits

All study content is sourced from and credited to:
- [Karan Pratap Singh](https://github.com/karanpratapsingh) — system-design repo
- [Donne Martin](https://github.com/donnemartin) — system-design-primer repo

This project is a study aid built on top of their incredible free work. Go star their repos!
