# Traveler

Traveler is a responsive travel agency landing page built with plain HTML, CSS, and JavaScript. It showcases travel packages and popular destinations, introduces the Traveler brand, and provides a newsletter signup interface.

## Features

- Responsive navigation with a mobile menu and sticky header
- Light and dark theme toggle
- Travel service categories and upcoming package cards
- Popular destination cards with hover descriptions
- About Us section with responsive image and text layout
- Scroll-triggered text and card animations, with reduced-motion support
- Newsletter email field and submit button

## Run Locally

No build tools, package installation, or server are required. Open `index.html` in a web browser. In VS Code, you can also use the Live Server extension to preview the page locally.

Google Fonts and Boxicons are loaded from CDNs, so an internet connection is needed for those fonts and icons. Page images are stored locally in `images/`.

## Project Structure

```text
.
├── index.html   # Page content and sections
├── styles.css   # Layout, responsive rules, themes, and animations
├── script.js    # Sticky header, mobile navigation, and theme toggle
└── images/      # Logo, service, package, and destination imagery
```

## Page Sections

- **Home:** Introductory hero and Get Started link
- **Services:** Summer stays, mountain tours, ship cruises, and food tours
- **Packages:** Featured trips with destinations, durations, prices, and ratings
- **Popular Destinations:** Destination cards with hover descriptions
- **About Us:** Traveler overview and supporting image
- **Newsletter:** Email input and submit control
- **Footer:** Quick links, support links, contact details, and social icons

## Notes

The newsletter form is currently presentation-only. It does not submit or store email addresses because no backend or mailing-list service is connected. Several navigation and footer links are placeholders and may need real destinations before deployment.
