# New Year's Eve Countdown

A lightweight New Year's Eve countdown with a dark neon style and a live timer based on the viewer's local time zone.

## Features

- Counts down to the next New Year's Day
- Updates every second
- Works on desktop and mobile screens
- Requires no build tools or external dependencies

## Project structure

```text
public/index.html   Main page, styles, and countdown logic
project.toml        Project metadata
```

## Run locally

Clone or download this repository, then run a local web server from the project folder:

```bash
py -m http.server 8000 --directory public
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

If `py` is unavailable, use `python` instead:

```bash
python -m http.server 8000 --directory public
```

You can also open `public/index.html` directly in a browser, although a local server is recommended.

## Customize

Edit `public/index.html` to change the text, colors, layout, or countdown styling. The countdown automatically uses the visitor's local time zone.
