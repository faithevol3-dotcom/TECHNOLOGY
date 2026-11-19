# TECHNOLOGY
WEBSITE
# Tecnology
website
# Technology in Daily Life

A simple one-page website that shows how technology fits into an ordinary day, where it helps most, and how to use it in a healthy way.


## Features

- **A day with tech:** Switch between Morning, Midday, Evening and Night to see everyday tools such as alarms, maps, mobile money, video calls and sleep tracking. The page colour changes with the time of day.
- **Where technology helps most:** Six areas: communication, health, money, learning, getting around and home.
- **Use it well:** An interactive checklist of six healthy tech habits with a progress bar and a short message.
- **Responsive:** Works on phones, tablets and computers.
- **Light and dark mode:** Follows the device setting automatically.
- **Accessible:** Keyboard focus is visible, tabs and the checklist work with a keyboard, and animations are reduced for people who prefer less motion.

## Project structure

```
technology-in-daily-life.html   # The whole site: HTML, CSS and JavaScript in one file
README.md                       # This file
```

## How to run

1. Download `technology-in-daily-life.html`.
2. Double-click it to open it in any modern browser.

No installation, build step or server is needed.

## Technology used

- HTML5, CSS3 and vanilla JavaScript (no frameworks or libraries)
- Google Fonts: Bricolage Grotesque and Newsreader (with system font fallbacks if offline)

## How to customize

- **Change the day content:** Edit the `DAY` object in the `<script>` section. Each time of day has a label, a time range and a list of items.
- **Change the habits:** Edit the `HABITS` array in the `<script>` section.
- **Change colours:** Edit the CSS variables at the top of the `<style>` section (`--bg`, `--ink`, `--accent`, and the `.stage[data-t=...]` colours).
- **Change the text:** Edit the headings and paragraphs directly in the HTML.

## Ideas for next steps

- Add more topics such as AI, smart homes or cybersecurity
- Add photos or illustrations
- Add a language switcher
- Add pages for specific topics, such as mobile money in Uganda

## License

Free to use and adapt for personal or educational projects.

