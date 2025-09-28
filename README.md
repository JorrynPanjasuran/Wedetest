🌍 Earth Sustainability Website

A responsive, multi-page website developed for Earth Sustainability, an environmental NGO focused on education, reforestation, and sustainable living. This project forms part of the WEDE5020 Portfolio of Evidence (Part 2) and demonstrates the application of HTML5, CSS3, and JavaScript alongside GitHub version control and professional documentation.

📖 Table of Contents

Project Overview

Features

How the Website Works

Installation

Usage

File Structure

Technologies Used

Code Attribution

Changelog

References

License

📌 Project Overview

The Earth Sustainability Website is designed to raise awareness about environmental issues while offering practical ways for users to get involved. It provides information about the organisation’s mission, team, values, and impact, alongside interactive features such as donation options, volunteer sign-ups, and a small eco-shop.

This project was built with a mobile-first approach, ensuring full responsiveness across devices and accessibility through ARIA labels and semantic HTML.

✨ Features
Navigation & Layout

Fixed responsive navigation bar with hamburger menu for mobile.

Hero video background with image fallback for performance.

Accessible navigation with ARIA labels and keyboard navigation support.

Content Sections

Mission & Vision: Statement of purpose with supporting imagery.

Team & Core Goals: Two-column layout introducing the team and goals.

Values Grid: Cards highlighting six organisational values with icons.

Impact Statistics: Animated counters showing real-world achievements.

Get Involved: Three-column grid with options to Volunteer, Donate, and Shop.

Interactive Features

Scroll-to-top button that appears on scroll.

Animations on scroll using Intersection Observer API.

Dynamic statistic counters that increment when visible.

Contact form with live character count and validation.

Donation modal system with fixed tiers and custom input.

Eco shop filters by category, price, and keyword search.

Toast notifications for user feedback (success, error, info).

Footer

Social media icons (SVG).

Quick links and contact information.

Newsletter signup with form validation.

🖥️ How the Website Works

Homepage (index.html)

Introduces Earth Sustainability with a hero banner, call-to-action, and navigation links.

About Us (about.html)

Explains the mission, vision, values, team members, and measurable impact through statistics.

Donate (donate.html)

Includes donation tiers (R50, R100, R200) and a custom donation modal.

Uses JavaScript to validate input and display success/error notifications.

Shop (shop.html)

Product listings with images, price, and category data attributes.

JavaScript-based filter system (by price, category, and search keyword).

Placeholder cart and order-by-email functionality.

Contact Us (contact.html)

Contact form with validation (required fields, email format, phone format).

Live character counter for messages.

Google Maps embed showing organisation location.

JavaScript Features (scripts.js)

Handles mobile navigation, scroll animations, form validation, stat counters, donation modal, and shop filters.

Includes utility functions for smooth scrolling and toast notifications.

📥 Installation

Navigate into the project folder:

cd earth-sustainability


Open index.html in your browser.

To test all functionality (e.g., animations, shop filters), ensure JavaScript is enabled.

🚀 Usage

Navigate through pages using the menu bar.

Scroll to trigger animations and stat counters.

On Contact Us, submit the form to see validation and character counting.

On Donate, select a tier or open the custom donation modal.

On Shop, filter products by category, price, or search keyword.

Use the back-to-top button to return quickly to the header.

📂 File Structure
earth-sustainability/
│
├── index.html
├── about.html
├── donate.html
├── shop.html
├── contact.html
│
├── css/
│   └── styles.css
│
├── js/
│   └── scripts.js
│
├── _images/
│   ├── logo.png
│   ├── hero.jpg
│   ├── mission.jpg
│   └── earth_sustainability_video.mp4
│
└── README.md

🛠️ Technologies Used

HTML5 – Semantic markup, accessibility, SEO meta tags.

CSS3 – Responsive grid/flexbox layout, animations, custom styles.

JavaScript (ES6) – DOM manipulation, validation, animations, interactive features.

GitHub – Version control and collaboration.

Google Maps Embed API – Location display.

SVG Icons – Lightweight scalable graphics for social media links.

📑 Code Attribution

MDN Web Docs – JavaScript APIs, HTML, CSS references.

W3Schools – Tutorials on modals, back-to-top button, shopping cart basics.

CSS-Tricks – Guides on flexbox, number animations, toast notifications.

Bootstrap – Navbar responsive structure (inspiration, custom-coded).

Google Developers – SEO meta tags and best practices.

Google Maps Platform – Map embed.

W3C & ARIA – Accessibility and keyboard navigation patterns.

FontAwesome – Social media icons (SVG usage).

WHATWG HTML Spec – Doctype and HTML structure.

📆 Changelog
2025-09-18

Initial setup of repository with index.html.

Added base folder structure (css/, js/, _images/).

2025-09-20

Implemented video background in homepage with fallback image.

Added responsive navigation bar with mobile hamburger menu.

2025-09-21

Added About Us page with Mission, Vision, Values, and Team sections.

Implemented grid layout for Values cards.

2025-09-22

Added Contact Us page with form validation and character counter.

Embedded Google Maps iframe.

2025-09-23

Created Donate page with tiered donations and custom modal.

Implemented donation form validation in scripts.js.

2025-09-24

Developed Shop page with product grid.

Implemented filters: category, price, and search.

Added add-to-cart notification system (placeholder cart).

2025-09-25

Added statistic counters to About page.

Implemented Intersection Observer for scroll animations.

2025-09-26

Improved form validation (email regex, phone regex, privacy checkbox).

Added toast notification utility function.

2025-09-27

Finalised footer section with SVG icons, newsletter form, quick links.

Added scroll-to-top button with smooth scroll.

2025-09-28

Documentation: Added README.md, code attribution, and Harvard bibliography.

Cleaned code with comments for accessibility, SEO, and usability.

📚 References
Harvard Style Bibliography

Bootstrap. (2025). Navbar documentation. [online] Available at: https://getbootstrap.com/docs/5.3/components/navbar/
 [Accessed 28 Sep. 2025].

CSS-Tricks. (2025). Intersection Observer and scroll animations. [online] Available at: https://css-tricks.com/
 [Accessed 28 Sep. 2025].

FontAwesome. (2025). Official SVG icons. [online] Available at: https://fontawesome.com/icons
 [Accessed 28 Sep. 2025].

Google Developers. (2025). SEO starter guide. [online] Available at: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
 [Accessed 28 Sep. 2025].

Google Maps Platform. (2025). Maps Embed API. [online] Available at: https://developers.google.com/maps/documentation/embed
 [Accessed 28 Sep. 2025].

MDN Web Docs. (2025). JavaScript, HTML & CSS references. [online] Available at: https://developer.mozilla.org/
 [Accessed 28 Sep. 2025].

W3C. (2025). Accessibility guidelines (WAI-ARIA). [online] Available at: https://www.w3.org/WAI/standards-guidelines/aria/
 [Accessed 28 Sep. 2025].

W3Schools. (2025). JavaScript tutorials. [online] Available at: https://www.w3schools.com/js/
 [Accessed 28 Sep. 2025].

WHATWG. (2025). HTML Living Standard. [online] Available at: https://html.spec.whatwg.org/
 [Accessed 28 Sep. 2025].

📜 License

This project is for academic purposes as part of the IIE WEDE5020 Portfolio of Evidence. All rights reserved © 2025.
