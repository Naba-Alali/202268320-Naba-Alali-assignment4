# 202268320-Naba-Alali-assignment4  
Assignment4  

---

## Project Description
This project is the final version of my personal portfolio website developed throughout the course. It builds on previous assignments and combines all features into one complete and functional web application.

The website presents my background as a Software Engineering student, showcases my projects, and includes interactive features such as project filtering, a quote generator, and a contact form. The design follows a consistent brown and beige theme to create a clean and warm user interface.

---

## Objectives
The main goals of this project are:
- Build a complete personal portfolio web application  
- Combine all previous features into one project  
- Improve user experience and visual design  
- Ensure responsiveness across different devices  
- Organize code in a clean and structured way  
- Use AI tools responsibly during development  

---

## Features

### About Section
- Displays personal introduction and background  
- Shows skills using chips (HTML, CSS, JavaScript, etc.)  
- Includes GitHub and LinkedIn links  
- Displays a greeting message based on time of day  
- Includes a visitor timer that tracks time spent on the page  
- Features a code-style card that presents personal information  

---

### Quote Section (API Integration)
- Fetches and displays a random quote from an external API  
- Users can generate a new quote by clicking a button  
- Displays a loading message while fetching  
- Shows an error message if the request fails  

---

### Projects Section
- Displays multiple projects with images and descriptions  
- Includes filter buttons (All, Web Apps, UI/UX)  
- Users can filter projects dynamically based on category  
- Selected filter is saved using localStorage  
- Each project has a **More Details button**  
- Clicking the button opens a modal with more information  

---

### Contact Section
- Form with Name, Email, and Message fields  
- Client-side validation:
  - Name must be at least 2 characters  
  - Email must be valid  
  - Message must be at least 5 characters  
- Displays error messages when input is invalid  
- Shows a success message after submission  

---

### Interactivity
- Theme toggle (light/dark mode) using localStorage  
- Greeting message based on time of day  
- Visitor timer updates dynamically  
- Project filtering with saved state  
- Modal popup for project details  
- Back-to-top button appears when scrolling  

---

### Animations & UI Effects
- Hover effects on navigation links and buttons  
- Card hover animation with glow effect  
- Smooth transitions across the website  
- Image zoom effect on project cards  
- Typing effect inside the code card  

---

## Technologies Used
- HTML5 : Structure and semantic layout  
- CSS3 : Styling, layout, animations, and themes  
- JavaScript (Vanilla JS) : Interactivity, API integration, and logic  
- Git & GitHub : Version control and repository management  

---

## Folder Structure
- `index.html` – Main webpage  
- `css/styles.css` – Styling and responsive design  
- `js/script.js` – JavaScript logic and features  
- `assets/images/` – Images used in the project  
- `docs/ai-usage-report.md` – AI tools usage report  
- `docs/technical-documentation.md` – Technical documentation  
- `presentation/slides.pdf` – Presentation slides  
- `presentation/demo-video.mp4` – Project demo video  

---

## How to Run Locally
1. Download or clone the repository  
2. Open `index.html` using Live Server or any modern browser  
3. Make sure you are connected to the internet for the quote API  

---

## How to Use the Website

Users can navigate the website using the navigation bar at the top, which links directly to the About, Projects, and Contact sections.

In the About section, users can view personal information and see a code-style card that presents information in a structured format.

In the Quote section, users can click "Generate Quote" to display a new quote from the API.

In the Projects section, users can filter projects using the buttons. Clicking "More Details" opens a modal window with more information.

In the Contact section, users can fill out the form. Validation ensures correct input, and a success message appears after submission.

Users can also switch between light and dark mode, and the website remembers their preference.

---

## AI Use (Short Summary)
AI tools such as ChatGPT were used to:

- Understand assignment requirements  
- Help debug JavaScript issues  
- Assist in API integration  
- Improve layout and styling  
- Suggest UI/UX improvements  
- Assist in writing documentation  

All AI-generated content was reviewed, modified, and tested to ensure correctness.

More details are provided in: `docs/ai-usage-report.md`

---

## Responsive Testing
The website was tested to ensure:
- All features work correctly  
- Project filtering works properly  
- Quote API loads and handles errors  
- Modal opens and closes correctly  
- Form validation works  
- Theme toggle saves user preference  
- Layout is responsive on different screen sizes  
- No console errors are present  

---

## Learning Outcomes
Through this assignment, I learned:
- How to build a complete web application  
- How to integrate APIs into a project  
- How to manage dynamic content using JavaScript  
- How to improve UI/UX design  
- How to debug and clean code  
- How to structure a professional portfolio  

---

## Live Demo
 https://naba-alali.github.io/202268320-Naba-Alali-assignment4/


 ## Demo Video
 https://youtu.be/prJ-tjhCC-g