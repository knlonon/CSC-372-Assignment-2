# CSC-372-Assignment-2
 CSC 372-01 — Assignment 2  
Author: Keith Lonon  
Date: 09.18.2026

## Project Description
The UNCG Campus Event Guide is a two‑page responsive website designed to help students discover upcoming campus activities. The site highlights events such as music nights, involvement fairs, hackathons, film festivals, and service projects. The intended audience is UNCG students looking for academic, social, and community engagement opportunities.

## Layout Decisions
### Flexbox Usage
- **Header navigation:** Flexbox aligns the logo and navigation links horizontally.
- **Hero section:** Flexbox places text and the hero image side‑by‑side on wide screens.
- **Footer navigation:** Flexbox centers and spaces footer links.
- **Related events:** Flexbox with `flex-wrap` allows cards to wrap on smaller screens.

### Grid Usage
- **Upcoming events grid (index.html):** CSS Grid displays event cards in responsive columns, including wide cards using `grid-column: span 2`.
- **Event details layout (event.html):** A two‑column grid separates the main content and sidebar on desktop screens.

### Testing
Pages were tested using:
- Chrome DevTools responsive mode  
- Mobile presets (iPhone SE, Pixel 7, iPad)  
- Manual resizing to confirm grid and flex behavior  

## Semantic HTML
The project uses meaningful semantic elements:
- **header:** Contains site branding and navigation.
- **nav:** Groups navigation links for both header and footer.
- **main:** Wraps the primary content of each page.
- **section:** Organizes hero, events, about, and related content.
- **article:** Represents individual event cards.
- **aside:** Sidebar for event details.
- **figure + figcaption:** Provides accessible image descriptions.
- **time:** Marks event dates with machine‑readable attributes.

