# SSAB Badminton Tournament Website

A responsive, browser-based 32-player single-elimination tournament manager.

## Included
- Edit 32 player names
- Random draw generation
- Five rounds: Round of 32, Round of 16, Quarter-finals, Semi-finals and Final
- Match score entry and automatic winner advancement
- Tournament dashboard, recent results and champion display
- Local browser saving with `localStorage`
- Export a JSON backup
- Print the bracket
- Mobile-friendly layout

## Run it
1. Extract the ZIP file.
2. Open `index.html` in a browser.
3. Add your actual players and tournament details.
4. Click **Generate random draw**.
5. Select a ready match, enter scores, and click **Save result & advance winner**.

You can also host the folder on GitHub Pages or another static website host.

## Important notes
- This is a front-end version: data stays in the browser/device where you use it.
- It does not currently sync updates across multiple phones. For that, connect a backend such as Firebase or Supabase and add authentication for the organiser.
- The score fields choose a winner based on the larger number entered. For a best-of-three tournament, enter a score that represents the match result and use the optional score note to record full game scores, e.g. `21-16, 18-21, 21-12`.
- This version is a single-elimination draw: 32 players require 31 matches.
