<div align="center">

<img src="apple-touch-icon.png" alt="HabitGrid logo" width="96" height="96">

# HabitGrid

**A GitHub-inspired habit tracker. One square per day, the darker the green, the stronger the day.**

Built as one of my first projects while learning web development.

[**Open the app**](https://kris102.github.io/HabitGrid/) · [**Live demo**](https://kris102.github.io/HabitGrid/?demo) · [Report a bug](https://github.com/Kris102/HabitGrid/issues)

![HTML](https://img.shields.io/badge/HTML5-single%20file-e34f26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-f7df1e?logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/dependencies-none-4ade80)
![License](https://img.shields.io/badge/license-MIT-blue)

</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/66e92086-b8b5-495e-bb15-c2eea449a77f" />
" />
" alt="HabitGrid screenshot" width="800">
</div>

## About

HabitGrid is a habit tracking web app inspired by the GitHub contribution graph. Its heatmap lets you see your daily habits at a glance, track consistency, and build better routines over time. There is no signup, no server and no tracking.

## Features

- **Heatmap grid** for every habit, with multiple intensity levels per day
- **Four views:** compact, year, month and week
- **Streaks:** current and longest streak for each habit
- **[FocusTime](#focustime):** stopwatch, Pomodoro or manual entry, with notes for each session
- **Targets:** log focus time against long-term goals or one-time tasks, with optional habit linking
- **Local-first:** all data stays in your browser's `localStorage`
- **Export and import:** JSON, CSV, and an "Export for AI" summary of your sessions
- **Weekly auto-backup:** saves a backup file to a folder you choose (Chrome and Edge), with a download reminder on other browsers
- **Demo mode:** add `?demo` to the URL to see a filled-in grid (nothing is saved)
- **Mobile friendly** and keyboard accessible

## How to use

1. Open the [live app](https://kris102.github.io/HabitGrid/), or try the [demo](https://kris102.github.io/HabitGrid/?demo) first.
2. Add a new habit by clicking **+** at the bottom.
3. Click a square to log a day.
4. Save your data every now and then with **Export JSON**, or turn on the weekly backup.

**Prefer to use it offline?** Download `index.html`, open it in your browser, and bookmark it.

## FocusTime

HabitGrid also has a built-in focus timer called **FocusTime**, opened with the stopwatch button in the toolbar. It tracks *how long* you work on something, while the grid tracks *whether* you showed up.

<!-- Optional: add a FocusTime screenshot
<div align="center">
  <img src="focus-time.png" alt="FocusTime screenshot" width="800">
</div>
-->
<img width="952" height="693" alt="Screenshot 2026-11-19 at 7 34 22 PM" src="https://github.com/user-attachments/assets/091e41c1-82ba-4b0e-a99b-b228c7efaf36" />

**Three ways to log time**

| Mode | What it does |
|---|---|
| **Stopwatch** | Counts up while you work, then saves the session |
| **Pomodoro** | Focus and break cycles (25 / 5 minutes by default, adjustable) |
| **Manual** | Add a session after the fact with the date, minutes and a note |

**What you can do**

- Pick a **target** for each session: one of your habits, a **long-term goal** (a language, an instrument, an exam), or a **one-time task** that gets finished.
- Add a short **note** to every session.
- See your totals for **Today, 7 days, 30 days, 90 days or All time**, filtered by long-term or one-time, with a chart of where your time went.
- Turn on **habit linking** so a habit's square on the grid is filled in automatically once you log enough focus time (20 minutes by default, adjustable). Squares you change by hand are left alone.
- Choose which habits appear in the focus timer.
- **Export for AI** creates a Markdown summary of your sessions (totals, active days, averages, weekly breakdown) that you can paste into an AI assistant to get a review of your study habits.
- Export your sessions as **CSV** or include them in the **JSON** backup.

## Your data and privacy

- Everything is stored in your browser on your device. Nothing is sent anywhere.
- Clearing your browser data will delete your habits, so export a backup regularly.
- Data does not sync between devices. To move it, export on one device and import on the other.

## Run locally

No build step and no dependencies. It is a single HTML file.

```bash
git clone https://github.com/Kris102/HabitGrid.git
cd HabitGrid
```

Open `index.html` in your browser, or serve it locally:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Project structure

```
HabitGrid/
├── index.html            # the entire app (HTML + CSS + JS)
├── favicon.svg           # site icon
├── apple-touch-icon.png  # home screen icon
├── screenshot.png        # README preview
└── README.md
```

## Tech

Plain HTML, CSS and JavaScript. No frameworks, no bundler, no external requests.

## Contributing

Suggestions and pull requests are welcome. For bigger changes, please open an issue first.

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-idea`
3. Commit: `git commit -m "Add my idea"`
4. Push: `git push origin feature/my-idea`
5. Open a pull request

## Author

**Krishank Joy**

[GitHub](https://github.com/Kris102) · [LinkedIn](https://www.linkedin.com/in/krishank-joy-905221291/)

## License

Released under the [MIT License](LICENSE).

---

<div align="center">

If HabitGrid helps you stay consistent, consider giving it a ⭐

</div>
