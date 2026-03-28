# Multimedia Portfolio Website

This is a responsive website designed to showcase muiltimedia services such as video productio and audio recording.
The site includes multiple pages and uses CSS Grid and Flexbox for layout.

---

## Issues Found
The starter code contained several issues:
- Duplicate CSS selectors causing style conflicts
- Navigation bar not responsive on smaller screens
- Grid layouts breaking due to fixed column structures
- Missing responsive adjustments for portfolio and footer
- Form validation styles not visible due to missing borders
- Overly rigid selectors (e.g. `nth-of-type`) causing layout inconsistencies
- Lack of accessibility features such as focus states

---

## Features

- Responsive layout
- Nvigation bar with active links
- Portfolio gallery using CSS Grid
- Contact form with validation
- Media section with video, audio, and embedded content
- Animated UI elements such as hover effects and transitions

---

## Technologies Used

- HTLM5
- CSS3 (Flexbox and Grid)
- Basic form validation using HTML and CSS

---

## Project Structure

/fix-and-complete-advanced-html-structure-ItumelengMphuti
│── index.html
│── about.html
│── media.html
│── contact.html
│── styles.css
│── /media
├── /images

---

## Design Desicions

- CSS Grid was used for page layouts to create structured sections.
- Flexbox was used for smaller components like the navigation and cards.
- Reusable classes like `.card` and `.portfolio` were used to maintain consistency.
- Media queries to ensure responsiveness on smaller screens.

---

## Cross-browser Compatibility
- Used `-webkit-` properties for gradient text support
- Added fallback colors for unsupported browsers
- Tested layout in multiple browsers (Chrome, Edge)

---

## Challenges

- Duplicate CSS selectors caused style conflicts.
- Input validation styles were not visible due to missing borders.
- Grid layout placement issues using `nth-of-type`.

---

## Solutions

- Merged duplicate CSS rules.
- Added border styling for form inputs.
- Adjusted layout structure and selectors.

---

## How to Run

1. Download or clone the repository
2. Open `index.html` in a browser
3. Navigate through pages using the navbar

---

## Future Improvements

- Add JavaScript for form submission
- Improve accessibility
- Add backend integration for contact form
- Optimize images and performance

---

## Screenshots

### Pages on desktop

Home Page
![Homepage Screenshot](screenshots/Home-page.png)

About Page
![Aboutpage Screenshot](screenshots/About.png)

Media Page 
![Media page Screenshot](screenshots/media1.png)
![Media page Screenshot](screenshots/media2.png)

Contact Page
![Contact Page Screenshot](screenshots/contact.png)

### Page mobile view

Home Page - Mobile View
![Home Page Screenshot](screenshots/home-mobile1.png)
![Home Page Screenshot](screenshots/home-mobile2.png)

Contact Page - Mobile View
![Contact Page Screenshot](screenshots/contact-mobile1.png)
![Contact Page Screenshot](screenshots/contact-mobile2.png)

## Form Validation
![Form Validation](screenshots/form-validation.png)

## Effects
![Effects](screenshots/effects.mp4)

### Media Elements
![Media](screenshots/media-elements.mp4)

### Flexbox Layout
![Flexbox](screenshots/Flexbox.png)

### CSS Grid Layout
![Grid](screenshots/CSS-grid.png)

### Browser Compatibility
![Chrome](screenshots/compatibility-chrome.png)
![Edge](screenshots/compatibility-edge.png)