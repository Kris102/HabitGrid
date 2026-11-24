<div align="center">

<img src="apple-touch-icon.png" alt="HabitGrid logo" width="96" height="96">

# HabitGrid

**A habit tracker that looks like a GitHub contribution graph.**
One square per day. The darker the green, the stronger the day.

[**Live demo**](https://YOUR_USERNAME.github.io/habitgrid/?demo) · [**Open the app**](https://YOUR_USERNAME.github.io/habitgrid/) · [Report a bug](https://github.com/YOUR_USERNAME/habitgrid/issues)

![HTML](https://img.shields.io/badge/HTML5-single%20file-e34f26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-f7df1e?logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/dependencies-none-4ade80)
![License](https://img.shields.io/badge/license-MIT-blue)

</div>

<!-- Add a screenshot or GIF here:
![HabitGrid screenshot](screenshot.png)
-->
<img width="733" height="689" alt="Screenshot 2026-11-19 at 7 31 42 PM" src="https://github.com/user-attachments/assets/568ea5fb-3699-4f4c-8c10-30361e440df1" />
<img width="952" height="693" alt="Screenshot 2026-11-19 at 7 34 22 PM" src="https://github.com/user-attachments/assets/671ec73b-8585-4deb-8844-42f199057623" />


## Why did I HabitGrid?

I wanted consistency to be visible at a glance, the same way a contribution graph shows a year of commits. HabitGrid is a small, fast, private tracker with no signup, no server and no tracking.

## Features

- **Contribution-style grid** for every habit, with multiple intensity levels per day
- **Four views:** compact, year, month and week
- **Streaks:** current and longest streak for each habit
- **Built-in timer:** stopwatch, Pomodoro or manual entry, with notes for each session
- **Targets:** log focus time against longer or shorter goals, not just daily habits
- **Local-first:** all data stays in your browser's `localStorage`
- **Export and import:** JSON, CSV, and an "Export for AI" summary of your sessions
- **Weekly auto-backup:** saves a backup file to a folder you choose (Chrome and Edge), with a download reminder on other browsers
- **Demo mode:** open the app with `?demo` to see a filled-in grid (nothing is saved)
- **Mobile friendly:** responsive layout, installable to the home screen
- **Keyboard accessible** with visible focus styles

## Try it

| | Link |
|---|---|
| Live app | https://YOUR_USERNAME.github.io/habitgrid/ |
| Demo with sample data | https://YOUR_USERNAME.github.io/habitgrid/?demo |

## Run locally

No build step and no dependencies. It is a single HTML file.

```bash
git clone https://github.com/YOUR_USERNAME/habitgrid.git
cd habitgrid
```

Then open `index.html` in your browser. To serve it locally instead:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy your own copy

1. Fork this repository.
2. Go to **Settings → Pages**.
3. Set **Source** to `Deploy from a branch`, pick `main` and `/ (root)`, then click **Save**.
4. Your site will be live at `https://YOUR_USERNAME.github.io/habitgrid/` in a minute or two.

## Your data and privacy

- Everything is stored in your browser on your device. Nothing is sent anywhere.
- Clearing your browser data will delete your habits, so use **Export JSON** or the weekly backup regularly.
- Data does not sync between devices. To move it, export on one device and import on the other.

## Project structure

```
habitgrid/
├── index.html            # the entire app (HTML + CSS + JS)
├── favicon.svg           # site icon
├── apple-touch-icon.png  # home screen icon
└── README.md
```

## Tech

Plain HTML, CSS and JavaScript. No frameworks, no bundler, no external requests.

## Roadmap

- [ ] Optional reminders
- [ ] Light theme
- [ ] More chart types for session history
- [ ] Import from other habit trackers

Have an idea? [Open an issue](https://github.com/YOUR_USERNAME/habitgrid/issues).

## Contributing

Pull requests are welcome. For larger changes, please open an issue first so we can talk it through.

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-idea`
3. Commit your changes: `git commit -m "Add my idea"`
4. Push: `git push origin feature/my-idea`
5. Open a pull request

## License

Released under the [MIT License](LICENSE).

---

<div align="center">

If HabitGrid helps you stay consistent, consider giving it a ⭐

</div>
