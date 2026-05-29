# ⏱️ MeetingMeter

**What's this meeting actually costing?**

Real-time cost clock that tracks how much money your meeting is burning through. Add attendees with hourly rates, hit start, and watch the dollars tick up — then share the shocking total on Slack or Twitter.

<p align="center">
  <img src="assets/icon-512.png" width="128" alt="MeetingMeter icon">
</p>

---

## ✨ Features

| Feature | Description |
|---|---|
| 💰 **Real-Time Cost Ticker** | Per-second cost updates with animated display |
| 👥 **Preset Roles** | CEO ($200/hr), Engineer ($100/hr), Designer ($85/hr), PM ($110/hr), and more |
| ✏️ **Custom Rates** | Any role, any rate — up to $5,000/hr |
| 📊 **Per-Person Breakdown** | See exactly what each attendee costs during the meeting |
| 🛑 **Dramatic STOP Button** | Pulsing red glow — visually satisfying to end the meeting |
| 📋 **Shareable Results** | One-tap copy formatted breakdown for Slack, Twitter, or email |
| 📜 **Meeting History** | Last 20 meetings saved locally |
| 🌗 **Dark Theme** | Looks great on any screen |
| 📱 **PWA** | Install on any device, fully offline |

---

## 🚀 Quick Start

```bash
python3 -m http.server 8080 -d meetingmeter
# Open http://localhost:8080
```

---

## 🎯 Use Cases

- **Managers** — justify ending unproductive meetings early
- **Agencies** — show clients what scope creep actually costs
- **Freelancers** — track billable meeting time visually
- **Fun** — screenshot the counter at $1,000+ and post it

---

## 💰 Monetization

| Tier | Price | Features |
|---|---|---|
| Free | $0 | Up to 5 attendees, full history |
| Pro | $1.99 | Unlimited attendees, custom roles, no limits |

---

## 🧩 Architecture

```
meetingmeter/
├── index.html         # Complete app — inline CSS + JS
├── manifest.json      # PWA manifest
├── sw.js              # Service worker (offline)
└── assets/
    ├── icon-192.png   # PWA icon
    └── icon-512.png   # PWA icon
```

Single-file PWA — no dependencies, no build step.

---

## 📄 License

MIT

---

<p align="center"><b>Built by <a href="https://github.com/Nezam-Seraj">Nezam Seraj</a></b></p>
