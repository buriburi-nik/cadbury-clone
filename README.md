# Cadbury Homepage

This project is a **Cadbury-themed homepage**, showcasing the brand's essence with a responsive, visually rich interface. It features modern web design elements, multimedia integration, and a focus on user experience.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Code Overview](#code-overview)
- [Live Demo](#live-demo)
- [Setup Instructions](#setup-instructions)
- [Project Structure](#project-structure)
- [Credits](#credits)

---

## Features

### General
- **Responsive Design**: Adapts seamlessly to desktop, tablet, and mobile screen sizes.
- **Modern Aesthetic**: Uses gradients, animations, and high-quality imagery.
- **Brand Integration**: Fully themed around Cadbury’s branding and promotional campaigns.

### Key Sections
1. **Header**
   - Background video for a dynamic first impression.
   - Logo and a navigation bar with dropdown menus for `About`, `Explore`, and `Products`.
   - Search functionality and a mobile-responsive hamburger menu.

2. **Hero Section**
   - Highlights Cadbury's "Secret Santa" campaign with a bold heading, descriptive text, and a prominent call-to-action button.

3. **New Creations**
   - Showcases new Cadbury products with scrollable cards featuring hover animations.

4. **Promotions**
   - Engages users with visually appealing promotional banners for seasonal events like Christmas gifts and competitions.

5. **Cadbury Brands**
   - Interactive cards linking to individual brand pages like Dairy Milk, Twirl, and Bournville.

6. **Social Media Stories**
   - Displays Instagram-like image cards with hover effects.

7. **Footer**
   - Social media icons, links to terms and policies, and a Mondelez International logo.

---

## Technologies Used

### Frontend
- **HTML5**: Semantic structure, including `<header>`, `<nav>`, `<section>`, and `<footer>` tags.
- **CSS3**: 
  - Flexbox for layout and alignment.
  - Media queries for responsiveness.
  - Custom animations (e.g., hover effects, sliding transitions).

### External Libraries
- [Font Awesome](https://fontawesome.com): For social media icons and dropdown arrows.
- [Google Fonts](https://fonts.google.com): `Lora` and `Open Sans` fonts for a clean, modern look.

---

## Code Overview

### HTML Highlights
1. **Header**:
   - Integrated a `<video>` element as a background.
   - Dropdown menus with a hover-triggered `dropdown-content` div.
   - Responsive logo and mobile navigation.

2. **Main Content**:
   - Card-based layout for product listings and brand highlights.
   - Embedded promotional videos and animated banners.

3. **Footer**:
   - Divided into a `footer-top` (logo and social links) and `footer-bottom` (legal links and copyright).

### CSS Highlights
1. **Global Styles**:
   - Box model normalization with `* { margin: 0; padding: 0; box-sizing: border-box; }`.
   - `body` styling with custom fonts and overflow management.

2. **Hero Section**:
   - Large gradient-styled text for headings.
   - Button hover effects with transitions.

3. **Cards**:
   - `scroll-snap-type` for horizontal scrolling in product listings.
   - Hover effects to scale cards and enhance visual feedback.

4. **Media Queries**:
   - Breakpoints for devices at `1024px`, `768px`, and `480px`.
   - Adjustments for font sizes, padding, and layout reflows on smaller screens.

5. **Custom Scrollbar**:
   - Styled horizontal scrollbar for the cards section.

6. **Animations**:
   - `@keyframes` for sliding cards.
   - Hover-triggered transformations for buttons, cards, and images.

---

## Live Demo

Explore the live demo here: [Cadbury Homepage](https://buriburi-nik.github.io/cadbury-clone/nikhil/HomePage/index.html)

---

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd cadbury-homepage
