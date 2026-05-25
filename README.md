# Tobacco Barrier

Tobacco Barrier is a standalone web app that helps users track their quit-smoking journey with a daily calendar, cigarette count logging, cost tracking, and motivational quotes.

## Features

- Set a quit decision date before starting the tracker.
- View a month-by-month calendar from the quit date up to today.
- Mark each day as smoke-free or smoked.
- Record the number of cigarettes smoked on any past or current day.
- Track total cigarettes smoked after the quit date.
- Track estimated money wasted based on a fixed cost of Rs. 25 per cigarette.
- Read randomized motivational quotes.
- Store progress locally in the browser using `localStorage`.
- Responsive layout for desktop and mobile screens.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage`
- Google Fonts

## Folder Structure

```text
Tobacco Barrier/
|-- TobaccoBarrier.html
|-- README.md
`-- .gitignore
```

## Installation

No package installation is required because this is a static single-file web app.

1. Clone or download this project.
2. Open the project folder in PowerShell.
3. Open `TobaccoBarrier.html` in a web browser.

## Run Commands

Open the HTML file directly from PowerShell:

```powershell
Start-Process ".\TobaccoBarrier.html"
```

Optional local server method:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/TobaccoBarrier.html
```

## Data Storage

The app does not use a backend server or database. User data is saved only in the current browser through `localStorage`.

Stored browser keys:

- `tb_logs`
- `tb_quit_date`

Clearing browser site data will remove saved progress.

## Author

Muzammil
