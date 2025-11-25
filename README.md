# Cliqtrix — Lost & Found Assistance

This is a small static website (single HTML file) with a header, sections, and a Zoho SalesIQ chat widget.

## Preview locally
Open the `bot.html` file in your browser. From PowerShell run:

```powershell
Invoke-Item 'C:\Users\TANISHKA\OneDrive\Desktop\cliqtrix 25\bot.html'
```

Or double-click the file in File Explorer.

## Quick edits you may want
- Replace the placeholder logo letter in the header (`.logo`) with an `<img>` tag.
- Update the email in the Contact section.
- Replace the `<link rel="icon" href="#">` with a real favicon path.

## Deploy to GitHub Pages
1. Create a new GitHub repository and push this folder (or just `bot.html` and `README.md`).
2. In GitHub repo settings, enable Pages from the `main` branch (or `gh-pages`) and set root as the publish folder.
3. The site will be available at `https://<your-username>.github.io/<repo-name>/bot.html`.

## Notes about SalesIQ
The SalesIQ widget script is included near the end of `bot.html`. It will load when you open the page. If you need it to load only on specific pages or require customization (pre-chat form, position, hide on mobile), tell me and I can modify the embed code.
