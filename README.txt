DISCIPLINE QUEST — FIRST WORKING VERSION

Included:
- Add, edit and delete daily missions
- Scheduled time, duration, icon and crown reward
- Focus timer with start, pause, resume and reset
- Completion celebration, crowns and XP
- Daily progress ring/bar, level and streak
- Missed-task carryover and crown deduction
- Local browser storage (progress stays on this device/browser)
- PWA manifest and service worker for installable use

RUN LOCALLY:
Open index.html in a modern browser. Timer and local saving work. PWA installation
requires serving the files over HTTPS (or localhost).

INSTALL ON ANDROID:
1. Upload the contents of this folder to a static HTTPS host (for example GitHub Pages).
2. Open the hosted URL in Chrome on Android.
3. Use Chrome menu > Install app / Add to Home screen.

IMPORTANT:
- This is a first-version, single-device prototype. Data is stored in browser localStorage.
- Clearing browser site data can erase progress. There is no cloud sync or account backup yet.
- The app runs as a daily routine: completed missions repeat the next day; unfinished
  missions carry forward. Missed tasks cost 3 crowns each, capped at 15 per missed day.
- Notifications and background alarm sounds are not included yet.
