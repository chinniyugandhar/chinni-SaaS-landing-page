# Chinni – SaaS Landing Page

Landing page for **Chinni**, a sample shift-scheduling tool for small shops, cafés and clinics.


## Run locally
No install needed. Open `index.html` in any browser.
(Optional: `python -m http.server 8000`, then visit http://localhost:8000)

## Technologies
- HTML5, CSS3 (grid, flexbox, CSS variables, light/dark mode)
- Vanilla JavaScript (no frameworks, no backend)
- Google Fonts: Bricolage Grotesque, Instrument Sans

## Sections and interactions
- Sticky navigation with smooth-scroll links and a mobile menu
- Hero with a working rota demo (tap cells to assign shifts; gaps turn yellow)
- Features, How it works, Pricing (monthly/yearly toggle)
- Demo request form with validation (name, email, plan) and a success message
- Get started / Choose plan buttons scroll to the form and pre-select the plan

## Design choices
I chose a scheduling tool for small teams and made the hero a working rota demo so visitors understand the product immediately. The page uses one teal accent and one yellow warning colour on a calm blue-grey base, with Bricolage Grotesque for headings and Instrument Sans for body text. Features are divided blocks instead of identical cards, and numbers appear only in the steps, where there is a real sequence. The layout is responsive with CSS grid and breakpoints at 760px and 900px. The form validates on blur and on submit.

## Screenshots
Add desktop and mobile screenshots in a `screenshots/` folder.
