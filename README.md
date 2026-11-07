# One UI 9 — Web Edition

A faithful, single-file web recreation of **Samsung One UI 9** (Android 17) with a complete setup experience, working apps, full gesture navigation, and **Samsung DeX** desktop mode.

Everything lives in one file: **`index.html`** — no build step, no dependencies. Open it in any modern browser (or serve it statically) and the phone boots up.

## What's inside

### First-run experience
- **Boot animation** — glowing SAMSUNG Galaxy splash
- **Setup wizard (10 steps)** — language, Wi-Fi, copy apps & data, Google & Samsung account sign-in, Google services, fingerprint enrollment, PIN creation with confirmation, navigation-bar choice, and finish
- **Lock screen** — One UI 9 adaptive clock, weather, glassy notifications, swipe-up unlock, PIN pad, and in-display fingerprint

### Home & system
- Glass clock/weather widgets, 4-column app grid, dock, page dots, Finder-style search
- **App drawer** — swipe up from home or the gesture bar, with live search
- **Notification shade + Quick Panel** — swipe down from the status bar; Wi-Fi/Bluetooth/Sound toggles, standalone **Dark mode** button (new in One UI 9), brightness slider, media player with waveform animation, live notifications
- **Recents** — swipe up and hold on the gesture bar; card carousel with close-all
- **Power menu & AOD** — side power key (screen off → always-on display), volume rocker with edge HUD
- Dark mode, 4 switchable wallpapers, 6 accent color palettes, ripples, spring animations, haptics and UI sounds throughout
- **Polish** — boot progress bar, home-screen unlock stagger, wallpaper parallax on page swipe, swipe-to-dismiss notifications

### Apps (16)
Phone (with call screen), Messages (with replies), Contacts, Internet browser, Camera (capture to Gallery), Gallery (with viewer), Clock (alarms, world clock, stopwatch, timer), Calendar, Calculator, Notes, Weather, My Files, Galaxy Store, Health, Settings, and the **Play Store**.

### Play Store (100+ apps)
A full Play Store experience with a 111-app catalog across 8 categories (Games, Social, Productivity, Entertainment, Lifestyle, Tools, Health & Fitness, Education):
- **For you** — editor's-choice hero, horizontal recommendation rows, per-category shelves
- **Top charts** — ranked top-25 list with ratings and downloads
- **Categories** — colored category tiles with full app lists
- **Search** — live filtering across the whole catalog
- **App pages** — screenshots, stats (rating / downloads / size / age), description, reviews
- **Install flow** — animated progress fill; installed apps get their own app screen, appear in the app drawer, and persist across reloads

### Settings (expanded)
Sounds and vibration (sound mode, volume slider, touch sounds), Notifications (Do not disturb, per-app toggles), Display (dark mode, brightness, Eye comfort shield, auto-rotate), Wallpaper and style (4 wallpapers + 6 accent color palettes), Lock screen and AOD (Default / Slim / Bold clock styles, AOD toggle), Security (full change-PIN flow with keypad), Battery (power saving, battery percentage), Digital Wellbeing (weekly screen-time chart, app timers), Software update (animated check), Wi-Fi, Accounts, and About phone — all as One UI-style subpages.

### Samsung DeX
Toggle DeX from the Quick Panel, the power menu, or Settings → Advanced features:
- Full desktop with taskbar, pinned + running apps, start-menu launcher, notification panel
- **Draggable, resizable windows** with minimize/maximize/close — run any app in a window

## Run it

```bash
# just open index.html, or:
python3 -m http.server 8080
```

Or visit the deployed preview. State (setup completed, theme, wallpaper, PIN, notes, photos) persists in localStorage — clear it to re-run the setup wizard.

## Notes

Fan-made recreation for demonstration purposes. Not affiliated with Samsung Electronics. Design references: [Samsung One UI 9](https://www.samsung.com/us/apps/one-ui/), [Samsung Newsroom](https://news.samsung.com/global/samsung-begins-official-rollout-of-one-ui-9-bringing-the-latest-galaxy-experiences-to-more-devices), [Engadget's One UI 9 roundup](https://www.engadget.com/2305270/samsung-one-ui-9-coolest-features/).
