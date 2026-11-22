# Storage Inventory

A one-page app for tracking what's in our storage unit, what's in the work room, and what's out at the apartment.

- **Drag bins** between Storage Unit, Work Room and Apartment. On a phone, press and hold a bin, then drag.
- **Order in the Storage Unit = position in the unit.** Top of the list is the front of the unit.
- **Tap a bin** to edit its name, what it looks like, its contents, and which months it's in season.
- **In season / Ready to go back** use those months to show what to pull out and what to return.
- **Search** finds which bin an item is in.
- **+ Add items** (top of the page) adds one or several items (comma-separated) to a bin, loose in a location, or a new bin, then asks whether to add another.
- **Colors = where things live.** Each location has a color (change it in Settings). Bins and items carry their home's color wherever they go; anything not in its home shows a colored "→ Home" tag, and the bar at the top counts what's out of place.

## Saving

Everything lives in `data.json` in this repo. Anyone can view the page; to save changes, open Settings (gear icon) and paste a fine-grained GitHub token with **Contents: Read and write** on this repository only. The token stays in that browser. Each save is a commit, so the repo history doubles as an undo log.
