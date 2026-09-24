# Look Busy

Twenty-one browser games dressed up as the apps you already have open at work. From across the office each one looks like the real thing, and every one of them has a panic button.

**Press `Esc` in any game** and it turns into dull, convincing work: a budget spreadsheet, an approved timesheet, a security settings page. Press it again to get back to your game. It works on the home page too.

This repo started life as `trelloclicker`, the Trello-looking idle clicker. That game is still here as **Taskwall**, alongside twenty others.

## Play

Open `index.html` in a browser. There's no build step and nothing to install.

Everything is plain HTML, CSS and JavaScript, one file per game. Fonts come from Google Fonts, and progress, high scores and streaks are saved in your browser's local storage.

To host it, turn on GitHub Pages for the repo (Settings → Pages → deploy from your branch, root folder). The home page is `index.html`.

## The games

| App | Pretends to be | Actually is | File |
| --- | --- | --- | --- |
| Threadline | Slack | Dungeon crawler | `threadline-chat.html` |
| Hubbub | Slack | Text adventure RPG | `hubbub-rpg.html` |
| Taskwall | Trello | Idle clicker | `taskwall-clicker.html` |
| Q3 Delivery Sprint | Trello | Deck-builder roguelite | `taskwall-deckbuilder.html` |
| Q3 Budget Forecast | Google Sheets | Minesweeper | `budget-minesweeper.html` |
| Team Calendar | Google Calendar | Tetris | `calendar-tetris.html` |
| Mail | Outlook | Inbox triage | `mail-inbox.html` |
| AdPilot | Google Ads | Bullet hell | `adpilot-bullethell.html` |
| Assistant | AI chat | Space Invaders | `assistant-invaders.html` |
| hole_01_final.psd | Photoshop | Pen tool golf | `pen-tool-golf.html` |
| Q3 Brand Review | Google Slides | Snake | `slides-snake.html` |
| Working on updates | Windows Update | Rhythm game | `update-rhythm.html` |
| My Network | LinkedIn | Whack-a-mole | `network-whack.html` |
| Task Manager | Task Manager | Tower defence | `task-defence.html` |
| Print Queue | Printer settings | Time management | `print-queue.html` |
| Weekly WIP sync | Teams | Flappy Bird | `meeting-flappy.html` |
| Timesheets | Harvest | Sudoku | `timesheet-sudoku.html` |
| Annual Leave | Workday | 2048 | `leave-2048.html` |
| Font Library | FontBase | Guess the font | `font-guess.html` |
| Swatches | Coolors | Colour matching | `swatch-match.html` |
| Password Reset | Okta | Rules puzzle | `password-rules.html` |

### New in this version

- **Timesheets.** A 9-day fortnight timesheet. Every project gets one hour a day, one per time slot and one per 3-day × 3-hour block. It's Sudoku, with three difficulties, draft notes, undo and a "ask your PM" hint that costs you 30 seconds.
- **Annual Leave.** 2048 in an HR portal. Half days merge into duvet days, long weekends, a week in Spain and up to a sabbatical (and early retirement if you're good). Arrow keys, WASD or swipe, with three withdrawals per leave year.
- **Font Library.** Guess the mystery typeface in six tries. Each miss reveals another glyph, and each guess shows whether its category and traits match. There's a daily font, a practice mode and an all-fonts hard mode, plus streaks and a copyable result for the team chat.
- **Swatches.** The client sends five "reference colours" and you match each one by eye with hue, saturation and brightness sliders against the clock. Scored with CIEDE2000, with a harder from-memory mode.
- **Password Reset.** Your password has expired, and the requirements get dafter one at a time: the digits must add up to 25, the Roman numerals must multiply to 35, it needs an orange hex code, today's weekday, the current hour, a leap year and its own length, all in under 64 characters.

### Fixes

- Weekly WIP sync no longer spills off the side of the screen on phones.
- The home page lists all 21 apps now that the roadmap has been built.

## Screenshots

The home page cards use the images in `shots/` (800 × 500 WebP, one per game).
