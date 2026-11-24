# 🚀 How to put this on your GitHub profile

## 1. Create the magic repo

Go to <https://github.com/new> and create a **public** repository named **exactly** your username:

```
MohammedQuraan24
```

Tick **"Add a README file"**. GitHub shows that repo's README at the top of your profile page. ✨

## 2. Copy these files into that repo

| This file | Put it at |
| :--- | :--- |
| `README.md` | repo root |
| `assets/banner.svg` | `assets/banner.svg` |
| `assets/divider.svg` | `assets/divider.svg` |
| `.github/workflows/snake.yml` | `.github/workflows/snake.yml` |

Then commit and push:

```bash
git add .
git commit -m "add my new profile README ✨"
git push
```

## 3. Turn on the snake animation 🐍

1. Open your new repo → **Actions** tab.
2. Click **"I understand my workflows, go ahead and enable them"** if asked.
3. Select **🐍 Generate contribution snake** → **Run workflow**.
4. Wait ~30 seconds. It will create an `output` branch holding `github-contribution-grid-snake.svg`.
5. After that it refreshes automatically every day at 23:37 UTC.

If the snake image doesn't show yet, refresh your profile in a couple of minutes.

## 4. Make it yours

Things worth editing in `README.md`:

- 📧 Your email (`mohammadhjdke@gmail.com`) is already in the contact badges and as a clickable line.
- 🔗 The **LinkedIn** and **X** links — replace `your-handle` with yours (or delete those badges).
- 📝 The short bio and the *"What's next"* checklist — make it sound like you.
- 🎨 Colors — the neon palette is `#00f5ff` (cyan), `#ff2bd6` (pink), `#8b5cf6` (violet). Change them in `assets/banner.svg` and in the stats card URLs.
- 🧩 Skills — add more icons from <https://skillicons.dev> by extending the `i=` list.

## 5. If your username is different

Replace **every** `MohammedQuraan24` in `README.md` and `snake.yml` with your real GitHub username.

---

**Done.** Visit <https://github.com/MohammedQuraan24> and enjoy your new profile. 🎉
