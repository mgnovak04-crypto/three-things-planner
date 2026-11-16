# Three Things Planner

A phone-first weekly planner built around one rule: three priorities a day, and everything else waits.

It has two separate spaces, Work and Personal, and the same loop in each:

- **Capture** puts anything on your mind into an inbox with one line and no sorting.
- **Week** holds three outcomes for the week and a day-by-day plan, with a flag on days that look heavy.
- **Today** shows the three priorities, each with a first step and a time estimate, plus anything carried over.
- **Now** is a full-screen timer for one task, with a place to park stray thoughts in the inbox.
- **Shut down the day** lists what got done and gives every open task a new home.

## Running it

The whole app is one file, `index.html`, with no build step.

- **Synced version:** published as a Claude artifact. Data is stored per signed-in user and stays in step between phone and laptop.
- **Standalone:** open `index.html` in a browser or host it as a static page. There is no sync in this mode. Everything is saved in that browser's local storage only.

## Data

Each task is one record: title, first step, estimate in minutes, space, day, whether it is one of the three, and time spent. A task is either in the inbox (no day) or on a day. Weekly outcomes are stored per week and space.
