# At The Races — starter prototype

First step: student registration page.

## Test locally
Open `index.html` in a browser. Try:
- `index.html?race=1&horse=horse-1`
- `index.html?race=1&horse=horse-2`
- `index.html?race=2&horse=horse-4`

## Publish with GitHub Pages
1. Create a repository called `at-the-races`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
5. GitHub Pages will provide the site URL.

Example QR destination:
`https://YOUR-USERNAME.github.io/at-the-races/?race=1&horse=horse-1`

## Prototype limitations
This version stores test records in that browser's local storage only. It does not share data between phones, nor provide a teacher dashboard. It is not ready for real student use. Next we need a shared database, session management, duplicate-selection rules and teacher controls. Get college approval for hosting and data handling before collecting real student information.
