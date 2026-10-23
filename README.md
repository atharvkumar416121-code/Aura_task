# Aura — Focus & Tasks (PWA)

A working productivity web app you can **open in any browser**, **install on Android**, and **share as a link**.

## Features

- Dashboard with stats, productivity chart, to-dos, activity, calendar
- Full task list with filters, priorities, due dates
- Pomodoro / Focus timer with XP rewards
- Command palette (⌘K / Ctrl+K)
- Light & dark mode
- Offline support via service worker
- Installable on Android (Add to Home Screen / Install app)
- Native share sheet on mobile
- LocalStorage persistence

## Run locally

```bash
cd aura-tasks-improved
npx serve .
# or: python3 -m http.server 8080
```

Open the URL shown (e.g. `http://localhost:3000`).

## Deploy (shareable link)

Any static host works. Easiest:

```bash
# Vercel
npx vercel

# Netlify
npx netlify deploy --prod --dir=.

# Or drag the folder onto https://app.netlify.com/drop
```

After deploy, share the HTTPS URL. Friends can open it on Android and install.

## Install on Android

1. Open the **HTTPS** link in **Chrome** (or Edge).
2. Tap the menu (⋮) → **Install app** or **Add to Home screen**.
3. Or wait for the in-app **Install** banner and tap it.
4. Aura opens full-screen like a normal app (no browser bar).

## Share

- Use the **Share** button in the app (uses Android’s share sheet).
- Or copy the website URL and send it via WhatsApp, Telegram, etc.

## Reset demo data

Tap **Reset demo** in the top banner (or run the command from ⌘K).

---

Built as an improved redesign of the original Aura dashboard demo.
