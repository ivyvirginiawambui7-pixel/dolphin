Replace the contents of `README.md` with this:

```markdown
# Maison Noir

A static restaurant website for a fine dining brand in Nairobi.

## Description

Maison Noir is a multi-page website built with HTML, CSS, and JavaScript. It includes a homepage, menu, about page, and contact page.

The JavaScript highlights the current page in the navigation and makes the reservation buttons reveal phone and email contact links. Reservations are not submitted online because the site does not have a booking backend.

## Project files

- `index.html` — homepage
- `menu.html` — menu page
- `about.html` — about page
- `contact.html` — contact page
- `style.css` — shared styles
- `script.js` — navigation and reservation-button interactions
- `.vscode/launch.json` — VS Code Chrome launch configuration
- `images/` — image assets used by the site

## View the site

You can open `index.html` directly in a web browser. Use the navigation links to visit the other pages.

## Run with VS Code debugging

The Chrome launch configuration expects the website to be served at `http://localhost:8080`.

1. Open a terminal in the project folder.
2. Start a local server with Python 3:

   ```powershell
   py -m http.server 8080
   ```

3. In VS Code, open **Run and Debug**.
4. Start **Launch Chrome against localhost**.

Stop the local server with `Ctrl+C` when you are finished.

## Deployment

This static website can be deployed to GitHub Pages, Netlify, Vercel, or another static hosting provider.

### GitHub Pages

1. Create a GitHub repository.
2. Add and push the project files to the repository.
3. Enable GitHub Pages in the repository settings.
4. Follow GitHub's instructions to open the published site.

### Netlify

1. Create a site in Netlify.
2. Deploy the project folder or connect the GitHub repository.
3. Netlify will provide a URL for the published site.

## Notes

- The site does not require a backend to display.
- The reservation buttons provide phone and email contact options; they do not book a table automatically.
- Update the page text, menu items, and image files to customize the site.
```

