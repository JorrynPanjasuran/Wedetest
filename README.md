| Section | Content |
|---------|---------|
| 🌍 Earth Sustainability Website | A responsive, multi-page website developed for **Earth Sustainability**, an environmental NGO focused on education, reforestation, and sustainable living. This project forms part of the **WEDE5020 Portfolio of Evidence (Part 2)** and demonstrates the application of **HTML5, CSS3, and JavaScript** alongside **GitHub version control** and professional documentation. |
| 📖 Table of Contents | 1. [Project Overview](#-project-overview)<br>2. [Features](#-features)<br>3. [How the Website Works](#-how-the-website-works)<br>4. [Installation](#-installation)<br>5. [Usage](#-usage)<br>6. [File Structure](#-file-structure)<br>7. [Technologies Used](#-technologies-used)<br>8. [Code Attribution](#-code-attribution)<br>9. [Changelog](#-changelog)<br>10. [References](#-references)<br>11. [License](#-license) |
| 📌 Project Overview | The **Earth Sustainability Website** is designed to raise awareness about environmental issues while offering practical ways for users to get involved. It provides information about the organisation’s mission, team, values, and impact, alongside interactive features such as donation options, volunteer sign-ups, and a small eco-shop.<br><br>This project was built with a **mobile-first approach**, ensuring full responsiveness across devices and accessibility through ARIA labels and semantic HTML. |
| ✨ Features | **Navigation & Layout**<br>- Fixed responsive navigation bar with hamburger menu for mobile.<br>- Hero video background with image fallback.<br>- Accessible navigation with ARIA labels and keyboard support.<br><br>**Content Sections**<br>- Mission & Vision<br>- Team & Core Goals<br>- Values Grid<br>- Impact Statistics<br>- Get Involved<br><br>**Interactive Features**<br>- Scroll-to-top button<br>- Animations on scroll<br>- Dynamic statistic counters<br>- Contact form with validation + char counter<br>- Donation modal system<br>- Eco shop filters<br>- Toast notifications<br><br>**Footer**<br>- Social media icons (SVG)<br>- Quick links & contact info<br>- Newsletter signup |
| 🖥️ How the Website Works | **Homepage (index.html)** – Hero banner, CTA, navigation links.<br>**About Us (about.html)** – Mission, values, team, statistics.<br>**Donate (donate.html)** – Tiers, custom donation modal, JS validation.<br>**Shop (shop.html)** – Product grid, filters, add-to-cart placeholder.<br>**Contact Us (contact.html)** – Form validation, character counter, Google Maps embed.<br>**JavaScript (scripts.js)** – Navigation, animations, validation, counters, donation modal, shop filters, notifications. |
| 📥 Installation | ```bash<br>cd earth-sustainability<br>```<br>Open `index.html` in your browser.<br>Ensure JavaScript is enabled for full functionality. |
| 🚀 Usage | - Navigate through pages using the menu bar.<br>- Scroll to trigger animations and stat counters.<br>- On Contact Us, submit the form to see validation and char counting.<br>- On Donate, select a tier or custom donation modal.<br>- On Shop, filter products by category, price, or keyword.<br>- Use the back-to-top button to return to header. |
| 📂 File Structure | ```<br>earth-sustainability/<br>├── index.html<br>├── about.html<br>├── donate.html<br>├── shop.html<br>├── contact.html<br>│<br>├── css/<br>│   └── styles.css<br>├── js/<br>│   └── scripts.js<br>├── _images/<br>│   ├── logo.png<br>│   ├── hero.jpg<br>│   ├── mission.jpg<br>│   └── earth_sustainability_video.mp4<br>└── README.md<br>``` |
| 🛠️ Technologies Used | - **HTML5** – Semantic markup, accessibility, SEO meta tags.<br>- **CSS3** – Responsive grid/flexbox, animations, styles.<br>- **JavaScript (ES6)** – DOM manipulation, validation, interactivity.<br>- **GitHub** – Version control.<br>- **Google Maps Embed API** – Location display.<br>- **SVG Icons** – Lightweight graphics. |
| 📑 Code Attribution | - MDN Web Docs – JavaScript APIs, HTML, CSS.<br>- W3Schools – Tutorials on modals, buttons, cart basics.<br>- CSS-Tricks – Flexbox, animations, notifications.<br>- Bootstrap – Navbar structure inspiration.<br>- Google Developers – SEO meta tags.<br>- Google Maps Platform – Map embed.<br>- W3C & ARIA – Accessibility guidelines.<br>- FontAwesome – SVG icons.<br>- WHATWG HTML Spec – HTML structure. |
| 📆 Changelog | **2025-09-18** – Project initialized. Created `index.html` as the homepage skeleton. Added base folder structure (`css/`, `js/`, `_images/`) to establish clean project organisation.<br><br>**2025-09-20** – Developed homepage hero section with **video background** and fallback image for slow connections. Implemented a fully responsive **navigation bar** with a mobile hamburger menu using JavaScript toggle functionality.<br><br>**2025-09-21** – Completed **About Us page**. Wrote Mission, Vision, and Team sections. Designed a **responsive values grid** using CSS Flexbox and Grid for improved layout on desktop and mobile.<br><br>**2025-09-22** – Built **Contact Us page**. Added form validation (required fields, email format, subject length). Implemented a **live character counter** for the message textarea. Embedded an interactive Google Maps iframe showing the organisation’s location.<br><br>**2025-09-23** – Designed **Donate page**. Added donation tiers (R50, R100, R200) with quick-select buttons. Created a **custom donation modal** with validation for minimum amount. Added JavaScript logic to simulate successful and failed submissions with notifications.<br><br>**2025-09-24** – Implemented **Shop page**. Designed product cards with images, hover overlays, quick-view placeholders, and add-to-cart buttons. Added **JavaScript-based filters** (category, price range, keyword search). Enabled placeholder cart functionality that triggers notifications when items are added.<br><br>**2025-09-25** – Added **statistic counters** to About page. Used JavaScript with Intersection Observer API to animate counters only when visible in the viewport. Enhanced scroll animations on value cards and news items for better engagement.<br><br>**2025-09-26** – Enhanced **form validation**: added regex for email and phone formats, minimum/maximum length checks, and Privacy Policy checkbox requirement. Created **toast notification utility** for consistent feedback messages (success, error, info).<br><br>**2025-09-27** – Finalised **footer design**. Added SVG social media icons (Facebook, Twitter, Instagram, LinkedIn). Completed **newsletter subscription form** with email validation. Implemented smooth **scroll-to-top button** that appears after scrolling down 300px.<br><br>**2025-09-28** – Conducted final cleanup and optimisation. Added detailed **README.md** with Features, Installation, Usage, Changelog, and Harvard-style References. Improved **accessibility** with ARIA labels and alt text for images. Reviewed SEO with meta descriptions and keywords. Tested full site responsiveness across devices. |
| 📚 References | - Bootstrap. (2025). *Navbar documentation*. [online] Available at: <https://getbootstrap.com/docs/5.3/components/navbar/> [Accessed 28 Sep. 2025].<br>- CSS-Tricks. (2025). *Intersection Observer and scroll animations*. [online] Available at: <https://css-tricks.com/> [Accessed 28 Sep. 2025].<br>- FontAwesome. (2025). *Official SVG icons*. [online] Available at: <https://fontawesome.com/icons> [Accessed 28 Sep. 2025].<br>- Google Developers. (2025). *SEO starter guide*. [online] Available at: <https://developers.google.com/search/docs/fundamentals/seo-starter-guide> [Accessed 28 Sep. 2025].<br>- Google Maps Platform. (2025). *Maps Embed API*. [online] Available at: <https://developers.google.com/maps/documentation/embed> [Accessed 28 Sep. 2025].<br>- MDN Web Docs. (2025). *JavaScript, HTML & CSS references*. [online] Available at: <https://developer.mozilla.org/> [Accessed 28 Sep. 2025].<br>- W3C. (2025). *Accessibility guidelines (WAI-ARIA)*. [online] Available at: <https://www.w3.org/WAI/standards-guidelines/aria/> [Accessed 28 Sep. 2025].<br>- W3Schools. (2025). *JavaScript tutorials*. [online] Available at: <https://www.w3schools.com/js/> [Accessed 28 Sep. 2025].<br>- WHATWG. (2025). *HTML Living Standard*. [online] Available at: <https://html.spec.whatwg.org/> [Accessed 28 Sep. 2025]. |









# 📘 CHRISTOFFEL FINE DINING APP – README

Below is the complete README in full-table format for GitHub.

---

# 📂 PROJECT OVERVIEW

| Category | Details |
|----------|---------|
| **Project Name** | Christoffel Fine Dining Mobile App |
| **Module** | MAST5112 – Part 3 Assessment |
| **Technologies Used** | React Native, TypeScript, Expo, React Navigation |
| **Developer** | ASIMIT SHRIVASTAVA |
| **Part 2 Achievement** | **98 percent** |
| **Reason for 2 percent loss** | Picker colours did not contrast well enough |
| **Fix Applied in Part 3** | Picker **text colour changed** to gold (#d4af37) and **background** changed to dark charcoal (#16171c) |

---

# 🍽️ APP FUNCTIONALITY SUMMARY

| Feature | Description |
|---------|-------------|
| **Welcome Screen** | Luxury hero image, overlay, title, tagline, CTA button |
| **Home Screen** | Shows all dishes, averages per course, remove functionality |
| **Add Item Screen** | Form with validation, picker, image preview, save/cancel |
| **Filter Screen** | Filters menu using for-loop logic |
| **Navigation** | Fully typed RootStackParamList |
| **Data Handling** | Items stored in array with typed MenuItem interface |
| **Validation** | Required fields + numeric checks |
| **Image Preview** | Displays provided URL |
| **Unique IDs** | Generated for each new dish |

---

# 🌟 PART 2 MARK BREAKDOWN

| Component | Result |
|-----------|--------|
| **Total Mark** | **98 percent** |
| **Lost Marks** | Picker colours lacked contrast |
| **Fix in Part 3** | Improved contrast for accessibility |

---

# 🎨 PICKER COLOUR FIX DETAILS

| Issue | Fix |
|-------|-----|
| Text too light | Set text to gold (#d4af37) |
| Background too bright | Changed to dark charcoal (#16171c) |
| Low contrast | Improved accessibility according to lecturer feedback |

---

# 📱 SCREEN-BY-SCREEN FUNCTIONALITY

## WELCOME SCREEN
| Feature | Description |
|--------|-------------|
| Background Image | Unsplash fine dining photography |
| Overlay | Increases text readability |
| Title | "CHRISTOFFEL" luxury branding |
| CTA | Navigates to Home |

---

## HOME SCREEN
| Feature | Description |
|---------|-------------|
| Item Counter | Shows number of dishes |
| Averages | Starters/Mains/Desserts averages via for-loops |
| FlatList | Renders menu items |
| Remove Button | Confirmation alert |
| UI | Gold-on-dark theme |

---

## ADD ITEM SCREEN
| Feature | Description |
|---------|-------------|
| Inputs | Name, description, price, image URL |
| Picker | Course selection with improved colours |
| Validation | Required fields + number check |
| Image Preview | Auto-loaded |
| Save/Cancel | Full form control |

---

## FILTER SCREEN
| Feature | Description |
|---------|-------------|
| Picker | Select course |
| Filtering Logic | For-loop filtering (Part 3 requirement) |
| Empty State | Friendly message when no results |

---

# 🔧 TECHNICAL DESIGN

| Area | Description |
|------|-------------|
| **TypeScript Types** | MenuItem, Course, RootStackParamList |
| **Navigation** | Strongly typed React Navigation |
| **State** | useState + props |
| **Performance** | useMemo |
| **Design Tokens** | Centralized colours |
| **Flexbox** | Used for layouts |

---

# 📚 HARVARD ANGLIA REFERENCES  

## CORE REACT NATIVE & TYPESCRIPT

| Reference |
|-----------|

Adobe Design Systems Team. 2025. *Design Tokens Overview*. Available at:  <https://spectrum.adobe.com/page/design-tokens/>  

Basarat Ali Syed. 2025. *TypeScript Deep Dive – Interfaces and Structural Typing*. Available at:  <https://basarat.gitbook.io/typescript/type-system>  

Material Design Team. 2025. *Elevation and Shadows in Modern Mobile UI*. Available at:  <https://m3.material.io/styles/elevation/overview>  

Material Design Team. 2025. *Modern Mobile UI Shadows and Layering Techniques*. Available at:  <https://m3.material.io/styles/elevation/overview>  

Meta Open Source. 2025. *Getting Started with React Native*. Available at:  <https://reactnative.dev/docs/getting-started>  

Meta Open Source. 2025. *React Native Components and APIs*. Available at:  <https://reactnative.dev/docs/components-and-apis>  

Meta Open Source. 2025. *React Native Flexbox Layout and UI Composition*. Available at:  <https://reactnative.dev/docs/flexbox>  

Meta Open Source. 2025. *React Native Form Layout and ScrollView Best Practices*. Available at:  <https://reactnative.dev/docs/scrollview>  

Meta Open Source. 2025. *React Native Image Component Guide*. Available at:  <https://reactnative.dev/docs/image>  

Meta Open Source. 2025. *React Native Input Handling, KeyboardAvoidingView, and Form Patterns*. Available at:  <https://reactnative.dev/docs/keyboardavoidingview>  

Meta Open Source. 2025. *React Native SafeAreaView Usage Guide*. Available at:  <https://reactnative.dev/docs/safeareaview>  

Meta Open Source. 2025. *React Native Shadow, Elevation, and Styling Guide*. Available at:  <https://reactnative.dev/docs/shadow-props>  

Meta Open Source. 2025. *React Native StyleSheet API Documentation*. Available at:  <https://reactnative.dev/docs/stylesheet>  

Meta Open Source. 2025. *React Native TextInput and Controlled Components*. Available at:  <https://reactnative.dev/docs/textinput>  

Meta Open Source. 2025. *TouchableOpacity Component Reference*. Available at:  <https://reactnative.dev/docs/touchableopacity>  

Microsoft TypeScript Team. 2025. *Advanced TypeScript Types – Union and Intersection*. Available at:  <https://www.typescriptlang.org/docs/handbook/advanced-types.html>  

Microsoft TypeScript Team. 2025. *Interfaces and Types – TypeScript Handbook*. Available at:  <https://www.typescriptlang.org/docs/handbook/2/everyday-types.html>  

Microsoft TypeScript Team. 2025. *Modules and Imports – TypeScript Handbook*. Available at:  <https://www.typescriptlang.org/docs/handbook/modules.html>  

Microsoft TypeScript Team. 2025. *Narrowing and Type Guards*. Available at:  <https://www.typescriptlang.org/docs/handbook/2/narrowing.html>  

Microsoft TypeScript Team. 2025. *React with TypeScript – Official Guide*. Available at:  <https://www.typescriptlang.org/docs/handbook/react.html>  

Microsoft TypeScript Team. 2025. *Typed Arrays and Iteration*. Available at:  <https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#arrays>  

Microsoft TypeScript Team. 2025. *Type Aliases and Literal Types*. Available at:  <https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#literal-types>  

Microsoft TypeScript Team. 2025. *TypeScript Functions and Return Types*. Available at:  <https://www.typescriptlang.org/docs/handbook/2/functions.html>  

Microsoft TypeScript Team. 2025. *Utility Types – TypeScript Handbook*. Available at:  <https://www.typescriptlang.org/docs/handbook/utility-types.html>  

Mozilla Developer Network. 2025. *JavaScript Number and Math Operations*. Available at:  <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number>  

Mozilla Developer Network. 2025. *JavaScript For Loop Guide*. Available at:  <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for>  

React Community. 2025. *Conditional Rendering Patterns*. Available at:  <https://react.dev/learn/conditional-rendering>  

React Community. 2025. *React Hooks – Managing State with useState*. Available at:  <https://react.dev/reference/react/useState>  

React Community. 2025. *React Hooks – useMemo for Performance Optimization*. Available at:  <https://react.dev/reference/react/useMemo>  

React Community. 2025. *Validating Inputs in React*. Available at:  <https://react.dev/learn/validating-inputs>  

React Navigation Contributors. 2025. *Bottom Tab Navigator Documentation*. Available at:  <https://reactnavigation.org/docs/bottom-tab-navigator/>  

React Navigation Contributors. 2025. *Native Stack Navigator Guide*. Available at:  <https://reactnavigation.org/docs/native-stack-navigator/>  

React Navigation Contributors. 2025. *Navigation Actions and Screen Lifecycle*. Available at:  <https://reactnavigation.org/docs/navigation-actions>  

React Navigation Contributors. 2025. *Navigating Between Screens*. Available at:  <https://reactnavigation.org/docs/navigating/>  

React Navigation Contributors. 2025. *React Navigation TypeScript Integration*. Available at:  <https://reactnavigation.org/docs/typescript/>  

React Navigation Contributors. 2025. *Strongly Typed Screens and Param Lists*. Available at:  <https://reactnavigation.org/docs/params/>  

React Native Community. 2025. *Optimising FlatList Configuration*. Available at:  <https://reactnative.dev/docs/optimizing-flatlist-configuration>  

React Native Community. 2025. *React Native TypeScript Cheatsheet*. Available at:  <https://react-typescript-cheatsheet.netlify.app/docs/basic/getting-started/>  

React Native Community. 2025. *Typography, Colors, and UI Guidelines*. Available at:  <https://reactnative.dev/docs/colors>  

Unsplash. 2025. *Unsplash Licensing Guide*. Available at:  <https://unsplash.com/license>  

W3C Design Tokens Community Group. 2025. *Design Tokens Format Specification*. Available at:  <https://design-tokens.github.io/community-group/format/>  

W3Schools. 2025. *Background Color – CSS Guide*. Available at:  <https://www.w3schools.com/css/css_background.asp>  

W3Schools. 2025. *Border Radius – CSS Reference*. Available at:  <https://www.w3schools.com/cssref/css3_pr_border-radius.php>  

W3Schools. 2025. *CSS Flex Direction Reference*. Available at:  <https://www.w3schools.com/cssref/css3_pr_flex-direction.php>  

W3Schools. 2025. *CSS Font Size Guide*. Available at:  <https://www.w3schools.com/css/css_font_size.asp>  

W3Schools. 2025. *CSS Icons – Reference Library*. Available at:  <https://www.w3schools.com/icons/>  

W3Schools. 2025. *CSS Justify Content Reference*. Available at:  <https://www.w3schools.com/cssref/css3_pr_justify-content.php>  

W3Schools. 2025. *CSS Letter Spacing Guide*. Available at:  <https://www.w3schools.com/cssref/pr_text_letter-spacing.php>  

W3Schools. 2025. *CSS Text Alignment Guide*. Available at:  <https://www.w3schools.com/css/css_text_align.asp>  

W3Schools. 2025. *How to Add a Bottom Navigation Bar*. Available at:  <https://www.w3schools.com/howto/howto_css_bottom_nav.asp>  

W3Schools. 2025. *JavaScript Arrays Guide*. Available at:  <https://www.w3schools.com/js/js_arrays.asp>  

StackOverflow Contributors. 2025. *Changing Background Colour with TypeScript*. Available at:  <https://stackoverflow.com/questions/74387658/changing-background-color-with-typescript>  

StackOverflow Contributors. 2025. *Controlling Touchable Area in React Native*. Available at:  <https://stackoverflow.com/questions/38955803/control-touchable-area-in-react-native>  

StackOverflow Contributors. 2025. *How to Change Font Size in JavaScript*. Available at:  <https://stackoverflow.com/questions/5586703/how-to-change-fontsize-by-javascript>  

StackOverflow Contributors. 2025. *How to Store Reference to Variable in Array*. Available at:  <https://stackoverflow.com/questions/5865094/how-can-i-store-reference-to-a-variable-within-an-array>  

StackOverflow Contributors. 2025. *React Icons in TypeScript – How to Declare Icons*. Available at:  <https://stackoverflow.com/questions/74190940/how-to-declare-react-icons-icon-in-ts>  

StackOverflow Contributors. 2025. *TypeScript Inference Issue with String Literal*. Available at:  <https://stackoverflow.com/questions/43121661/typescript-type-inference-issue-with-string-literal>  

StackOverflow Contributors. 2025. *Using BorderRadius and Border Colours in RN*. Available at:  <https://stackoverflow.com/questions/54112033/how-to-use-borderradius-and-borderleftcolor-borderbottomcolor-borderrightcolor>  

StackOverflow Contributors. 2025. *React Navigation Props and TypeScript*. Available at:  <https://stackoverflow.com/questions/60704310/typescript-stacknavigatonprops-and-screen-props-in-react-navigation-v5>  




