# Look Busy

Twenty-one browser games dressed up as the apps you already have open at work. From across the office each one looks like the real thing, and every one of them has a panic button.

**Press `Esc` in any game** and it turns into dull, convincing work: a budget spreadsheet, an approved timesheet, a security settings page. Press it again to get back to your game. It works on the home page too.

This repo started life as `trelloclicker`, the Trello-looking idle clicker. That game is still here as **Taskwall**, alongside twenty others.

## Play

**Online:** https://finleyobrien99-maker.github.io/trelloclicker/

Open `index.html` in a browser. There's no build step and nothing to install.

Everything is plain HTML, CSS and JavaScript, one file per game. Fonts come from Google Fonts, and progress, high scores and streaks are saved in your browser's local storage.

To host it, turn on GitHub Pages for the repo (Settings → Pages → deploy from your branch, root folder). The home page is `index.html`.

## The games

| App | Pretends to be | Actually is | File |
| --- | --- | --- | --- |
| Threadline | Slack | Dungeon crawler | `threadline-chat.html` |
| Hubbub | Slack | Text adventure RPG | `hubbub-rpg.html` |
| Taskwall | Trello | Idle clicker (the deep one) | `taskwall-clicker.html` |
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

### Taskwall, the deep version

The original Trello clicker has been rebuilt as a proper idle game. Old saves carry over.

- **14 roles to hire.** They run from Interns up to Multiverse Studios. Hire or let go in batches of 1, 10 or 100.
- **148 requests to approve.** Every role has seven upgrade tiers. There are also click upgrades, an intern buddy scheme, cross-team synergies, office perks and morale boosters.
- **106 trophies,** some of them secret. Each one adds 4% morale, and team socials turn morale into velocity.
- **Quick wins** come in five flavours: a lucky payout, "In the zone" (×7 velocity), "Deadline rush" (×777 clicks), a team surge and a free request.
- **Stakeholders** turn up and watch your board, siphoning velocity as they go. Click one to address its feedback and get back more than it took. The longer you leave them, the bigger the payout.
- **Epic cards** arrive every 25 cards, with 50 subtasks and a big payout.
- **Sprints** are timed challenges: 150 ticks in a minute, 12 cards in two minutes, or a points target.
- **The Kitchen** opens once you have 10 Interns. Coffee brews over time and you spend it on orders: stand-ups, biscuits, espresso, team breakfast, flat whites and a risky mystery brew.
- **Rebranding** is the prestige system. Once you've earned 1B points all time, rebrand the studio to win awards (+1% velocity each, for good) and spend them as clout on 15 permanent perks.
- **The office dog.** Approve the Office dog request and Biscuit wanders the board. Pet them for points, fill their mood bar to set off the zoomies (velocity ×2), and they'll fetch you quick wins. Five dog-only requests and five dog trophies to go with it.
- **Also:** an activity ticker, a full stats page, number format settings, save export and import, and offline earnings.

### New in this version

- **Timesheets.** A 9-day fortnight timesheet. Every project gets one hour a day, one per time slot and one per 3-day × 3-hour block. It's Sudoku, with three difficulties, draft notes, undo and a "ask your PM" hint that costs you 30 seconds.
- **Annual Leave.** 2048 in an HR portal. Half days merge into duvet days, long weekends, a week in Spain and up to a sabbatical (and early retirement if you're good). Arrow keys, WASD or swipe, with three withdrawals per leave year.
- **Font Library.** Guess the mystery typeface in six tries. Each miss reveals another glyph, and each guess shows whether its category and traits match. There's a daily font, a practice mode and an all-fonts hard mode, plus streaks and a copyable result for the team chat.
- **Swatches.** The client sends five "reference colours" and you match each one by eye with hue, saturation and brightness sliders against the clock. Scored with CIEDE2000, with a harder from-memory mode.
- **Password Reset.** Your password has expired, and the requirements get dafter one at a time: the digits must add up to 25, the Roman numerals must multiply to 35, it needs an orange hex code, today's weekday, the current hour, a leap year and its own length, all in under 64 characters.

### Fixes

- Weekly WIP sync no longer spills off the side of the screen on phones.
- The home page lists all 21 apps now that the roadmap has been built.
- Taskwall has been rebuilt from a simple clicker into a full idle game (see above).

## Screenshots

The home page cards use the images in `shots/` (800 × 500 WebP, one per game).
