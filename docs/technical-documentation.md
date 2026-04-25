# Technical Documentation

## 1. Project Overview

This project is an interactive personal portfolio website developed using HTML, CSS, and JavaScript. It represents the final version of the portfolio, combining all previous features into a complete and polished web application.

The website includes sections for About, Quotes, Projects, and Contact, and provides interactive features such as project filtering, a quote generator, a visitor timer, and a code-style information card to enhance the user experience.

---

## 2. Technologies Used

HTML was used to structure the content of the website using semantic elements such as navigation, sections, and forms.

CSS was used for styling, layout, and responsiveness. Flexbox and CSS Grid were used to create structured layouts. CSS variables were used to manage light and dark themes and maintain consistent colors across the website.

JavaScript was used to add interactivity, including theme switching, project filtering, modal functionality, form validation, API integration, typing effect, and timer logic.

Git and GitHub were used for version control and project management.

---

## 3. Project Structure

The project is organized as follows:

- index.html → main structure of the website  
- css/styles.css → styling and layout  
- js/script.js → interactivity and functionality  
- assets/images → images used in the project  
- docs → documentation files  
- README.md → project overview  

This structure helps keep the project organized and easy to maintain.

---

## 4. Features

### 4.1 Dynamic Content

The project includes a filtering system in the Projects section. Users can click buttons (All, Web Apps, UI/UX) to show or hide projects dynamically.

It also includes a code-style card that displays personal information in a structured format with a typing animation effect.

---

### 4.2 API Integration

The project integrates an external API to fetch random quotes. The data is retrieved using JavaScript and displayed dynamically on the webpage.

The application shows a loading message while fetching data and displays an error message if the API fails.

---

### 4.3 Complex Logic

The project includes additional logic beyond basic interaction:

- Project filtering based on selected category  
- Visitor timer that updates every second  
- Typing animation effect for displaying code content  
- Conditional logic for displaying time in seconds and minutes  

---

### 4.4 State Management

The project uses localStorage to store user preferences:

- Theme selection (light/dark mode) is saved and restored  
- Selected project filter is saved and applied on reload  

This ensures a consistent experience for users.

---

### 4.5 Interactivity

- Theme toggle button switches between light and dark mode  
- Modal window shows project details when clicking "More Details"  
- Quote generator updates dynamically  
- Visitor timer updates in real time  
- Back-to-top button appears when scrolling  
- Greeting message changes based on time of day  

---

### 4.6 Form Validation

The contact form validates user input:

- Name must be at least 2 characters  
- Email must follow a valid format  
- Message must be at least 5 characters  

Error messages are displayed when inputs are invalid.  
A success message is shown after successful submission.

---

### 4.7 Animations and Transitions

- Hover effects on navigation links and buttons  
- Card hover animation with glow effect  
- Smooth transitions across elements  
- Image zoom effect on project cards  
- Typing animation in the code card  

---

## 5. User Navigation and Interaction

Users can navigate between sections using the navigation bar.

The Projects section allows filtering of projects based on category. Each project includes a "More Details" button that opens a modal with additional information.

The Quote section allows users to generate quotes dynamically.

The Contact section allows users to submit messages with validation feedback.

Additional features such as theme toggle and back-to-top button improve navigation and usability.

---

## 6. Responsive Design

The website is responsive and works on different screen sizes.

- CSS Grid is used for project layout  
- Flexbox is used for navigation and layout alignment  
- Media queries adjust layout for tablets and mobile devices  

The design was tested using browser developer tools.

---

## 7. Accessibility

- Images include alt text  
- Form inputs include labels  
- Buttons use appropriate types  
- Colors provide sufficient contrast  

---

## 8. Testing

The project was tested to ensure:

- All features function correctly  
- Project filtering works and saves state  
- Quote API loads and handles errors  
- Modal opens and closes correctly  
- Form validation works properly  
- Visitor timer updates correctly  
- Theme toggle saves user preference  
- Layout adapts to different screen sizes  
- No console errors are present  

---

## 9. Performance

The website is optimized for performance:

- Images are stored locally and properly sized  
- Unused CSS and JavaScript code was removed  
- Files are organized and lightweight  
- No external libraries are used unnecessarily  

---

## 10. Learning Outcomes

Through this project, I learned:

- How to build a complete web application  
- How to integrate APIs into a project  
- How to implement dynamic JavaScript features  
- How to manage state using localStorage  
- How to improve UI/UX using animations and interactions  
- How to structure clean and maintainable code  

---

## 11. Conclusion

This project demonstrates improvement from previous assignments by combining multiple features into one complete application. It highlights my ability to build interactive front-end applications, manage user interaction, and create a consistent and professional design.

---