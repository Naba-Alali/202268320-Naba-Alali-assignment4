# 202268320-Naba-Alali-assignment3
Assignment3


## Project Description
This project is an improved version of my personal portfolio website developed in Assignment 2. In this assignment, I enhanced the website by adding more advanced features, integrating an external API, and improving the overall functionality and user experience using HTML, CSS, and JavaScript.

The website presents my background as a Software Engineering student, showcases my projects, and includes dynamic features such as filtering, a quote generator, and a visitor timer to make the site more interactive and engaging.

## Objectives
The main goals of this project are:
- Extend the portfolio from Assignment 2 with advanced features
- Integrate an external API to display dynamic data
- Implement more complex JavaScript logic
- Improve state management and user interaction
- Enhance performance and code organization
- Use AI tools responsibly to assist development

## Features
### About Section
  - Displays personal introduction and background
  - Includes roles, skills, and additional information
  - Shows dynamic greeting based on time of day
  - Displays a visitor timer that tracks how long the user stays on the page

## Quote Section (API Integration)  
  - Fetches and displays a random quote from an external API
  - Users can generate a new quote by clicking a button
  - Displays loading message while fetching data
  - Shows an error message if the API fails

### Projects Section
  - Displays multiple projects with images and descriptions
  - Includes filter buttons (All, Web Apps, UI/UX)
  - Users can filter projects dynamically based on category
  - Selected filter is saved using localStorage and restored on reload
  - Each project has a Details button that opens a modal with more information

### Contact Section
  - Form with Name, Email, and Message fields
  - Client-side validation:
    - Name must be at least 2 characters
    - Email must be valid
    - Message must be at least 5 characters
  - Displays error messages when input is invalid
  - Shows a loading message ("Sending...") and success message after submission

### Interactivity
  - Theme toggle (light/dark mode) using localStorage
  - Greeting message based on time of day (Good morning/afternoon/evening)
  - Visitor timer that updates every second
  - Project filtering based on user selection with saved state
  - Modal popup for project details
  - Back-to-top button appears when scrolling

### Animations & UI Effects
  - Hover effects on navigation links and buttons
  - Card hover animation with glow effect
  - Smooth transitions for better user experience
  - Image zoom effect on project cards


## Technologies used
  - HTML5 : Structure and semantic layout
  - CSS3 : Styling, layout, animations, and themes
  - JavaScript (Vanilla JS) : Interactivity, API integration, and logic
  - Git & GitHub : Version control and repository management

## Folder Structure
- `index.html` – Main webpage
- `css/styles.css` – Styling + responsive rules
- `js/script.js` – JavaScript logic and features
- `assets/images/` – Images used in the project
- `docs/ai-usage-report.md` – AI tools usage report
- `docs/technical-documentation.md` – Technical documentation

## How to Run Locally
1. Download or clone the repository
2. Open index.html using Live Server (recommended) or any modern browser
3. Make sure you are connected to the internet for the quote API


## How to Use the Website

Users can navigate the website using the navigation bar at the top, which links directly to the About, Projects, and Contact sections.

In the Projects section, users can click the filter buttons to display specific project categories. Clicking the "Details" button on a project opens a modal window with more information about that project.

In the Quote section, users can click the "Generate Quote" button to display a new quote fetched from the API. If the quote cannot be loaded, a friendly error message is shown.

In the Contact section, users can fill in their name, email, and message. If any field is invalid, the website displays error messages. If all inputs are valid, a success message appears after submission.

The theme button allows users to switch between light and dark mode, and the website remembers their choice. A back-to-top button also appears while scrolling to help users return to the top of the page easily.


## AI Use (Short Summary)
AI tools such as ChatGPT were used to:

- Understand assignment requirements
- Help debug JavaScript issues
- Assist in implementing API integration
- Improve layout and styling
- Suggest UI/UX improvements
- Assist in writing documentation

All AI-generated code was reviewed, modified, and tested to ensure correctness and understanding.

More details are provided in: (docs/ai-usage-report.md)


## Responsive Testing
The website was tested to ensure:
- All interactive features work correctly
- Project filtering updates dynamically and saves state
- Quote API loads correctly and handles errors
- Modal opens and closes properly
- Form validation works for valid and invalid inputs
- Visitor timer updates correctly
- Theme toggle saves user preference
- Layout is responsive on different screen sizes
- No console errors are present




## Learning Outcomes
Through this assignment, I learned:
- How to integrate external APIs into a web application
- How to implement more complex JavaScript logic
- How to manage application state using localStorage
- How to improve performance by cleaning unused code
- How to enhance user experience with dynamic features
- How to build a more advanced and interactive portfolio


