# At The Races — starter prototype

This is the first student registration prototype.

## One registration QR per race
The QR code opens the registration page for a race. Students choose one of the nine horses on the page.

Example QR destinations:
- `https://YOUR-USERNAME.github.io/at-the-races/?race=1`
- `https://YOUR-USERNAME.github.io/at-the-races/?race=2`
- `https://YOUR-USERNAME.github.io/at-the-races/?race=3`

## Test locally
Open `index.html` in a browser. Add `?race=2` or `?race=3` to test another race.

## Publish with GitHub Pages
1. Upload `index.html` to the repository root.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
4. GitHub Pages will provide the published website URL.

## Prototype limitations
Registrations are saved in that browser's local storage only. They are NOT shared between students' phones or visible to a teacher. This is not ready for real student use. Next we need a shared database, session management, duplicate-selection rules and teacher controls. Get college approval for hosting and data handling before collecting real student information.

## Current attempt points
- 1 attempt: 100
- 2 attempts: 50
- 3+ attempts: 25
