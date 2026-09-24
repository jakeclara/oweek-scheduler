# OWeek Scheduler

A lightweight, browser-based scheduling tool for orientation week coordinators. Build your full staff schedule, track event coverage, and export a clean read-only view to share with your team — no accounts, no subscriptions, no install required.

---

## Features

- **Day-by-day schedule** — set your OWeek dates and navigate each day via tabs
- **Event management** — define events with start/end times, location, color, and notes
- **Recurring events** — mark events as recurring and select which days of the week they apply; the tool tracks coverage per day automatically
- **Coverage checklist** — at a glance, see which events are fully placed, partially placed, or missing
- **Team management** — add and remove staff members; each becomes a column on the schedule grid
- **Click-to-place** — select an event, then click a team member's column to assign it; the tool prevents placing events on days they aren't scheduled for
- **Editable** — update any event or remove any assignment at any time
- **Font size toggle** — switch between S / M / L text on the grid for readability
- **Export** — download a standalone HTML file with day tabs and full color; shareable via chat, email, or Drive
- **Print** — print directly from the browser with colors intact

---

## Getting Started

1. Open `oweek.html` in any modern browser (Chrome recommended)
2. Go to **Setup** — enter your OWeek start and end dates
3. Go to **Team** — add your staff members
4. Go to **Events** — add your events with times, colors, and notes
5. Click any event to select it, then click a team member's column on the grid to place it
6. Repeat across each day tab until coverage is complete
7. Hit **Export** to download the shareable schedule

---

## Sharing the Schedule

The tool saves your data automatically to your browser's local storage — no account needed.

To share the schedule with your team:

- Click **Export** to download `oweek-schedule.html`
- Send the file via group chat, email, or upload to Google Drive
- Anyone can open it in a browser — no login, no install

---

## Notes

- Data is stored in your browser's local storage and persists between sessions on the same device
- The exported schedule bakes in the current font size — set S/M/L before exporting
- Recurring events are defined once and can be placed on each applicable day independently
- Non-recurring events are locked to the day you assign them; the tool will not allow placement on other days

---

## Built With

Plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step. One file.

Built in collaboration with [Claude](https://claude.ai) by Anthropic.
