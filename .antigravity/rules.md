# Instructions for Property Movement Realty Website

## Rules & Standards:
1. **Tech Stack**: HTML & CSS only (no external JS unless explicitly requested).
2. **Responsiveness**:
   - EVERY page and section MUST be fully responsive across all device breakpoints (Mobile: `<480px`, Tablet: `481px - 768px`, Laptop: `769px - 1024px`, Desktop: `>1024px`, and Ultra-wide).
   - Use fluid typography (clamp/rem), flexbox, CSS grid, and media queries automatically for every section.
   - Do not wait for the user to ask for responsiveness; it must be built-in from the start.
3. **Modular File Structure**:
   - Keep separate CSS files for each section/component (e.g., `css/navbar.css`, `css/hero.css`, `css/services.css`, `css/footer.css`, `css/global.css`).
   - Import them into a main `css/style.css` or link them cleanly in `index.html`.
