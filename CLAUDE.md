# Cassette Unlimited Website

## Project Overview
Static website for **Cassette Unlimited** — a New York City 70s/80s cover band.
Hosted on GitHub Pages, served at cassetteunlimited.com.

## Tech Stack
- Pure HTML/CSS/JS — no build tools, no frameworks
- Single `index.html` with inline styles for simplicity
- GitHub Pages for hosting

## Key Conventions
- **Upcoming shows** are maintained in the `#shows` section of `index.html`
- Each show is a `<div class="show-card">` block — copy an existing one as a template
- Shows should be ordered chronologically (soonest first)
- Past shows should be moved to a commented-out archive block or removed
- All dates should include day-of-week, full month name, and year

## Adding a New Show
1. Open `index.html`
2. Find the `<!-- SHOWS START -->` comment
3. Add a new `<div class="show-card">` block with: date, venue, address, times, ticket links, price
4. Commit and push — GitHub Pages auto-deploys

## Contact
- Email: info@cassetteunlimited.com
- Instagram: @cassetteunlimited
