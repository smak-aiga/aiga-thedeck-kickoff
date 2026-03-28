# The Deck 2026 — AIGA Dallas Kickoff
 
A web app built for the **The Deck 2026** kickoff event on March 25, 2025 at Local Public Eatery, Dallas. The Deck is a community project by AIGA Dallas in which 54 designers each illustrate a playing card featuring a DFW landmark.
 
This app rotated through all 54 landmark photos on a display screen while guests signed up to claim their card assignment via a linked Google Sheet.
 
## Note on Google Sheet sync
 
The live Google Sheet sync has been disconnected from this repo after the event to protect participant information. The app still displays all 54 landmarks and rotates normally — the sheet URL has simply been removed from the code.
 
If you fork this project for your own event, replace the `SHEET_CSV_URL` constant in `index.html` with your own published Google Sheet CSV link.

 ## How the Google Sheet worked
 
The app synced with a Google Sheet published as a CSV. Each row represented one landmark card, and the app read **column D (DESIGNER)** to determine whether a card had been claimed.

 <img width="3456" height="1994" alt="image" src="https://github.com/user-attachments/assets/f572e872-7a7d-47bc-9be3-66c69378d5f0" />

## How it works
 
- Landmark photos rotate automatically on a TV display
- Guests sign up in a Google Sheet to claim a landmark card
- The app syncs with the sheet every 30 seconds — claimed landmarks drop out of the rotation in real time
- Clicking the AIGA Dallas logo resets to an overview grid of all 54 landmarks
 
## Photo credits
 
All photos used in this project are either Creative Commons licensed, attributed to their authors, or in the public domain. Specific credits are displayed in the footer of the app when each photo is shown.
 
Licenses used include:
- **CC0 / Public Domain** — no attribution required
- **CC BY** — attribution required
- **CC BY-SA** — attribution + share-alike required
- **CC BY-NC** — attribution, non-commercial use
- **CC BY-NC-ND** — attribution, non-commercial, no derivatives
- **CC BY-NC-SA** — attribution, non-commercial, share-alike
 
Special thanks to **Michael Barera** (11 photos), **Carol M. Highsmith / Library of Congress**, **Renelibrary**, **Andreas Praefcke**, and **David Herrera** whose photographs appear multiple times throughout the project.
 
## Project
 
**The Deck 2026** is a 10th anniversary signature project of AIGA Dallas. Learn more at [aigadallas.org](https://aigadallas.org).
