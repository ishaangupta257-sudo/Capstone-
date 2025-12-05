# HealthyLife — Static Website

Simple, responsive static website for a demo healthcare clinic.

## Preview
Open [index.html](index.html) in a browser (or use VS Code Live Server) to view the site.

## Project Structure
- [index.html](index.html) — Home page with hero, services, and footer.
- [about.html](about.html) — About page describing the clinic.
- [contact.html](contact.html) — Contact page with a simple form.
- [style.css](style.css) — All styling, layout, animations and dark-mode rules.
- [script.js](script.js) — Theme toggle logic and persistence.

## Key Implementation Notes

### Theme toggle (script.js)
- The theme toggle button is the element with id `theme-toggle`. See [`themeToggle`](script.js).
- On load the script reads the saved theme from localStorage via [`currentTheme`](script.js) and applies it to the document [`body`](script.js).
- Clicking the toggle toggles the `dark-mode` state and saves it to localStorage.

Files and symbols:
- [`script.js`](script.js) — contains [`themeToggle`](script.js), [`currentTheme`](script.js), and logic that modifies the document [`body`](script.js).

### Styling and Dark Mode (style.css)
- Main layout, hero, service cards and footer are defined in [style.css](style.css).
- Theme button styles: see `.theme-btn` in [style.css](style.css).
- Dark mode styles are applied under the `.dark-mode` selector in [style.css](style.css).

Referenced selectors in this repo:
- `.theme-btn` — theme button styling ([style.css](style.css))
- `.dark-mode` — toggled dark-mode rules ([style.css](style.css))

## How to customize
- Content: edit the HTML files ([index.html](index.html), [about.html](about.html), [contact.html](contact.html)).
- Styles: change colors, fonts, spacing in [style.css](style.css).
- Theme behavior: update toggle logic in [script.js](script.js).

## Notes
- The contact form is static (no backend). To submit data, add form handling or integrate a service.
- External images/icons are loaded via remote URLs in HTML and CSS.

## License
This is a demo project — add your preferred license if distributing.
```// filepath: README.md

# HealthyLife — Static Website

Simple, responsive static website for a demo healthcare clinic.

## Preview
Open [index.html](index.html) in a browser (or use VS Code Live Server) to view the site.

## Project Structure
- [index.html](index.html) — Home page with hero, services, and footer.
- [about.html](about.html) — About page describing the clinic.
- [contact.html](contact.html) — Contact page with a simple form.
- [style.css](style.css) — All styling, layout, animations and dark-mode rules.
- [script.js](script.js) — Theme toggle logic and persistence.

## Key Implementation Notes

### Theme toggle (script.js)
- The theme toggle button is the element with id `theme-toggle`. See [`themeToggle`](script.js).
- On load the script reads the saved theme from localStorage via [`currentTheme`](script.js) and applies it to the document [`body`](script.js).
- Clicking the toggle toggles the `dark-mode` state and saves it to localStorage.

Files and symbols:
- [`script.js`](script.js) — contains [`themeToggle`](script.js), [`currentTheme`](script.js), and logic that modifies the document [`body`](script.js).

### Styling and Dark Mode (style.css)
- Main layout, hero, service cards and footer are defined in [style.css](style.css).
- Theme button styles: see `.theme-btn` in [style.css](style.css).
- Dark mode styles are applied under the `.dark-mode` selector in [style.css](style.css).

Referenced selectors in this repo:
- `.theme-btn` — theme button styling ([style.css](style.css))
- `.dark-mode` — toggled dark-mode rules ([style.css](style.css))

## How to customize
- Content: edit the HTML files ([index.html](index.html), [about.html](about.html), [contact.html](contact.html)).
- Styles: change colors, fonts, spacing in [style.css](style.css).
- Theme behavior: update toggle logic in [script.js](script.js).

## Notes
- The contact form is static (no backend). To submit data, add form handling or integrate a service.
- External images/icons are loaded via remote URLs in HTML and CSS.

## License
This is a demo project — add your preferred license if distributing.