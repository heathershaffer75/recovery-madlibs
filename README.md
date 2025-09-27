# Recovery Mad Libs: Character Edition

A lightweight, in-browser game for therapy groups where patients **and staff** become characters in funny, recovery‑themed Mad Libs. Runs entirely client‑side (no backend, no data collection), so it’s safe to use on shared machines.

## ✨ What’s in this repo
- **`index.html`** — Single‑file app with 10+ stories, random suggestions, and reveal/reset controls.
- **`assets/logo.svg`** and **`assets/favicon.svg`** — Simple logo & favicon (SVG).
- *(Optional)* Add a `CNAME` if you’ll use a custom domain.

## 🚀 Quick start
1. Download or clone the repo.
2. Open `index.html` in a modern browser.

> If your browser restricts local files, run a tiny local server: `python -m http.server` and visit `http://localhost:8000/`.

## 📚 Stories
Group Room Incident, Relapse Prevention Olympics, Saturday Special, Matinee Mayhem, Family Therapy Gone Wild, The Great Snack Heist, Meditation Meltdown, Missing Phone Mystery, Treatment Talent Show, Roommate Chronicles, Graduation Day Surprise.

## 🕹️ How to play
1. Pick a story.
2. Ask the group for words and type them in.
3. Click **🎲 Random** if folks are stuck.
4. **🎉 Reveal** the story.
5. **↺ Reset** to play again.

## 🔐 Privacy & tone
- 100% client‑side; nothing is uploaded or stored.
- Use first names or nicknames; avoid PHI.
- Keep the humor kind. The joke is in the absurd combinations, not people.

## 🌐 Publish with GitHub Pages
1. Push this repo to GitHub.
2. Settings → **Pages** → Source: `main` and root (`/`).
3. Save. Your site appears at `https://<user>.github.io/<repo>/`.

## 🧩 Customize
- Edit the inputs in each `<section>` to change the blanks.
- Add pools in the `POOLS` object for better random suggestions.
- Add new stories: create a new `<section>` and a `case` in the `reveal()` switch.

## 🧪 License
**CC BY 4.0** — You can share/adapt with attribution.
