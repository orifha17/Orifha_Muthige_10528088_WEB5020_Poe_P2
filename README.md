# Muthige Insurance Brokers — WEDE5020 Part 2

## Project overview
This is the Part 2 implementation of the Muthige Insurance Brokers website for WEDE5020 Web Development (Introduction). The project keeps the Part 1 content and brand direction while moving presentation into an external CSS stylesheet and adding responsive behaviour.

## Website pages
- `index.html` — homepage
- `about.html` — organisation story, mission and vision
- `services.html` — four cover categories
- `car.html` — car insurance
- `home.html` — home insurance
- `business.html` — business insurance
- `life.html` — life insurance
- `enquiry.html` — quote/enquiry form
- `contact.html` — contact details and map

## Part 2 implementation
### External CSS
All website pages link to `CSS/style.css`. The stylesheet controls the shared colour palette, typography, spacing, layout, cards, forms, navigation, buttons, footer and responsive breakpoints.

### Typography
The Part 1 proposal specified Poppins for headings and Inter for body copy. These fonts are loaded from Google Fonts, with Arial as a fallback.

### Colour palette
- Deep Teal: `#125E5E`
- Teal Dark: `#0B4545`
- Warm Amber: `#E8A33D`
- White: `#FFFFFF`
- Teal Soft: `#EAF5F4`
- Body text: `#183434`
- Muted text: `#5D6F6F`

### Layout and decoration
The site uses CSS Grid and Flexbox for the main page structures. Cards, forms, navigation, buttons and content sections use consistent spacing, borders, rounded corners and shadows.

### Pseudo-classes
The stylesheet includes `:hover`, `:focus-visible`, `:active`, `:last-child`, `:marker` and `:root` states where appropriate. Navigation, buttons, links and form controls have visible interaction states.

### Responsive design
The site uses breakpoints at 1000px, 780px and 560px. The desktop grid layouts collapse for tablet/mobile, the navigation changes to a hamburger menu, typography scales with `clamp()`, cards become single-column where required, and images remain fluid with `max-width: 100%` and `height: auto`.

### JavaScript
`JS/script.js` handles the mobile navigation toggle and front-end enquiry form feedback. The form is intentionally front-end only because this is a static HTML/CSS/JavaScript module project; no server-side submission system was provided.

## Part 1 feedback addressed
The Part 1 result and feedback identified improvements needed around comments/documentation, GitHub commits, README information, changelog, references, and some design/proposal items. Part 2 addresses the development/documentation items by: 
1. Adding explanatory comments to CSS and JavaScript.
2. Providing this detailed README.
3. Providing `CHANGELOG.md` with a dated development record.
4. Providing a clear `PART2_CHECKLIST.md` mapping the implementation to the Part 2 criteria.
5. Keeping the existing project references in the supplied Part 1 proposal PDF and documenting the use of Google Fonts.

## Folder structure
```text
My_project_webd/
├── CSS/
│   └── style.css
├── Images/
│   ├── business-insurance.svg
│   ├── car-insurance.svg
│   ├── home-insurance.svg
│   ├── life-insurance.svg
│   └── logo.svg
├── JS/
│   └── script.js
├── index.html
├── home.html
├── about.html
├── services.html
├── car.html
├── business.html
├── life.html
├── contact.html
├── enquiry.html
├── CHANGELOG.md
├── PART2_CHECKLIST.md
├── REFERENCES.md
├── README.md
└── WEDE5020_ICE_Task_01_ST10528088_Orifha_Muthige.pdf
```

## References
See `REFERENCES.md` for the project reference list.

## Running the website
Open `index.html` in a modern browser. For the most reliable local testing, serve the folder with a simple local web server. No build tools or frameworks are required.

## Notes
- The website is a static educational project.
- Insurance cover statements are kept general and refer to policy terms/risk assessment rather than promising specific benefits.
- The enquiry form demonstrates client-side interaction; it does not send data to a real server.
- The supplied Part 1 proposal PDF is retained in the project for submission context.
