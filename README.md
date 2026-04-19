# 📊 WhatsApp Goal Tracker

**Paste WhatsApp messages → Get a clean accountability dashboard.**

A simple, powerful tool for accountability groups on WhatsApp. Members post daily goal updates in a group chat, and this tool turns those messy messages into an organized dashboard — with a leaderboard, participation heatmap, and downloadable reports.

🔒 **100% offline. No data leaves your device.** Everything runs in your browser — no servers, no logins, no tracking.

---

## 🚀 Live Demo

👉 **[Try it here](https://srilekham0407-hub.github.io/Whatsapp-Goal-Tracker/)**

---

## 🎯 What It Does

1. **Paste** — Copy messages from your WhatsApp accountability group and paste them into the tool
2. **Auto-parse** — The tool automatically finds daily reports, ignores regular chats, and extracts goal statuses
3. **Dashboard** — View a clean dashboard with leaderboard, full status table, and participation summary

---

## ✨ Features

### Core
- **Smart message parsing** — Handles multiple WhatsApp date/time formats (Android, iPhone, WhatsApp Web)
- **Keyword-based goal matching** — Customize keywords for each goal so members can report in their own style
- **Automatic deduplication** — Paste overlapping message batches without worrying about duplicates
- **Cumulative data** — Paste multiple batches over days/weeks and data keeps accumulating

### Dashboard
- **Leaderboard** — Ranked by days posted and total points, with progress bars
- **Full Status Table** — Every report, every goal, color-coded (Yes/No/custom text)
- **Participation Summary** — Who posted and who missed, by date, with total days count
- **Date range filter** — View data for any custom time period
- **Member filter** — Filter any table by a specific member
- **Sortable columns** — Click any header to sort ascending/descending
- **Frozen columns** — First few columns stay pinned when scrolling wide tables
- **Row numbers** — Easy identification in large tables
- **CSV download** — Export leaderboard or full status data for further analysis

### Settings
- **Custom member list** — Add members with M.No and Name
- **Custom goals** — Add/edit/remove goals with emoji, label, and keywords
- **Backup & restore** — Download your settings as a JSON file, reimport anytime

---

## 📱 How to Use

### Step 1: Set Up (one-time)
1. Open the tool and go to the **Settings** tab
2. Add your group members (M.No, Name — one per line)
3. Customize goals and keywords to match your group's reporting style
4. Click **Save**

### Step 2: Paste Messages
1. Open your WhatsApp group
2. Select and copy the daily report messages
3. Go to the **Paste & Process** tab
4. Paste and click **Process Messages**

### Step 3: View Dashboard
- The tool automatically switches to the **Dashboard** tab
- View the leaderboard, status table, and participation summary
- Use date range and member filters to drill down
- Download CSV for sharing or further analysis

---

## 📋 Expected Message Format

Members post daily updates in your WhatsApp group like this:

```
M.No: 7
Date: 15/04/26

⏰ Wake up @ 5AM: Yes
🧘 Meditation: Yes
🚶 Walking: 5000 steps
💬 Affirmations: Yes
📖 Learning: Read 20 pages
🎯 Deep Work: 2 hours
📈 1% Goal Progress: Yes
🙏 Gratitude: Thankful for health
🏆 Today's Win: Finished project proposal
```

The tool is flexible — it matches by **keywords**, not exact format. So even casual reporting works.

---

## 🛠️ Technical Details

- **Single HTML file** — No build tools, no dependencies, no frameworks
- **Pure HTML + CSS + JavaScript** — Runs in any modern browser
- **LocalStorage** — Settings and data persist in your browser between sessions
- **Responsive design** — Works on desktop, tablet, and mobile
- **Zero external requests** — No CDN, no API calls, no fonts loaded from the internet

---

## 📂 File Structure

```
Whatsapp-Goal-Tracker/
├── index.html      ← The entire app (single file)
└── README.md       ← You're reading this
```

---

## 🤝 Contributing

Ideas, bug reports, and pull requests are welcome! If you use this for your accountability group and have suggestions, feel free to open an issue.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for accountability groups everywhere.**
