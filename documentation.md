# Multimedia Portfolio Website

This is a responsive website designed to showcase muiltimedia services such as video productio and audio recording.
The site includes multiple pages and uses CSS Grid and Flexbox for layout.

## Features

- Responsive layout
- Nvigation bar with active links
- Portfolio gallery using CSS Grid
- Contact form with validation
- Media section with video, audio, and embedded content
- Animated UI elements such as hover effects and transitions

## Technologies Used

- HTLM5
- CSS3 (Flexbox and Grid)
- Basic form validation using HTML and CSS

## Project Structure

/fix-and-complete-advanced-html-structure-ItumelengMphuti
│── index.html
│── about.html
│── media.html
│── contact.html
│── styles.css
│── /media
├── /images

## Design Desicions

- CSS Grid was used for page layouts to create structured sections.
- Flexbox was used for smaller components like the navigation and cards.
- Reusable classes like `.card` and `.portfolio` were used to maintain consistency.
- Media queries to ensure responsiveness on smaller screens.

## Challenges

- Duplicate CSS selectors caused style conflicts.
- Input validation styles were not visible due to missing borders.
- Grid layout placement issues using `nth-of-type`.

## Solutions

- Merged duplicate CSS rules.
- Added border styling for form inputs.
- Adjusted layout structure and selectors.

## How to Run

1. Download or clone the repository
2. Open `index.html` in a browser
3. Navigate through pages using the navbar

## Future Improvements

- Add JavaScript for form submission
- Improve accessibility
- Add backend integration for contact form
- Optimize images and performance
