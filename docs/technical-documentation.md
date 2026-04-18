# Technical Documentation

## 1. Project Overview

This project is an interactive personal portfolio website developed using HTML, CSS, and JavaScript. It is an improved version of Assignment 2 with added advanced features, including API integration, more complex logic, and better user interaction.

The website includes sections for About, Quotes, Projects, and Contact, and allows users to interact with dynamic features such as filtering projects, generating quotes, tracking time spent on the website, and submitting a contact form.

---

## 2. Technologies Used

HTML was used to structure the content of the website using semantic elements such as navigation, sections, and forms.

CSS was used for styling, layout, and responsiveness. CSS Grid and Flexbox were used to create structured layouts. CSS variables were used to manage light and dark themes.

JavaScript was used to add interactivity, including theme switching, project filtering, API integration, modal functionality, form validation, and timer logic.

Git and GitHub were used for version control and managing the project files.


---

## 3. Project Structure

The project is organized as follows:

- index.html → main structure of the website  
- css/styles.css → styling and layout  
- js/script.js → interactivity and functionality  
- assets/images → images used in the project  
- docs → documentation files  
- README.md → project overview   

This structure helps keep the project clean and organized.

---

## 4. Features

### 4.1 Dynamic Content

The project includes a filtering system in the Projects section. Users can click buttons (All, Web Apps, UI/UX) to show or hide projects dynamically.

It also includes a quote generator that displays a new quote when the user clicks a button.

---

### 4.2 API Integration

The project integrates an external API to fetch random quotes. The data is retrieved using JavaScript and displayed dynamically on the webpage.

The application shows a loading message while fetching data and displays a user-friendly error message if the API fails.

---
### 4.3 Complex Logic

The project includes additional logic beyond simple interactions:

- Project filtering based on category  
- Visitor timer that updates every second  
- Conditional display of time in seconds and minutes  

This demonstrates multi-step logic and real-time updates.

---

### 4.4 State Management

The project uses localStorage to store user preferences:

- Theme selection (light/dark mode) is saved and restored on reload  
- Selected project filter is saved and applied when the page reloads  

This ensures a consistent user experience.

---

### 4.5 Interactivity

- Theme toggle button switches between light and dark mode  
- Modal window shows project details when clicking “Details”  
- Quote generator updates content dynamically  
- Visitor timer updates in real time  
- Back-to-top button appears when scrolling  
- Greeting message changes based on time of day  

---

### 4.6 Form Validation

The contact form checks:

- Name must be at least 2 characters  
- Email must be valid  
- Message must be at least 5 characters  

If the input is invalid, error messages are displayed.  
If valid, a success message appears after a short delay.

---

### 4.7 Animations and Transitions

- Hover effects on buttons and navigation links  
- Card hover animation with movement and glow effect  
- Smooth transitions for better user experience  
- Image zoom effect on project cards  

---

## 5. User Navigation and Interaction

The website is designed so users can move easily between the main sections using the navigation bar. Each navigation link scrolls to the related section of the page.

The Projects section supports interaction through category filter buttons. These buttons allow users to control which projects are visible. Each project also includes a Details button that opens a modal with more information.

The Quote section includes a button that allows users to generate a new quote dynamically. The interface provides feedback while the quote is loading and also shows a message if the API request fails.

The Contact section is interactive and guides the user through form submission. Validation messages appear when fields are incomplete or invalid, and a success message is displayed after valid submission.

Additional interactive elements such as the theme toggle and back-to-top button help improve navigation and user experience.

## 6. Responsive Design

The website is responsive and works on different screen sizes.

- CSS Grid is used for project layout  
- Flexbox is used for navigation and form layout  
- Media queries adjust layout for tablets and mobile devices  

The layout was tested by resizing the browser and using developer tools.

---

## 7. Accessibility

- Images include alt text  
- Form inputs have labels  
- Buttons use proper types  
- Colors have good contrast for readability  

---

## 8. Testing

The project was tested to ensure:

- All features work correctly  
- Project filtering works and saves state  
- Quote API loads correctly and handles errors  
- Modal opens and closes  
- Form validation works  
- Visitor timer updates correctly  
- No console errors appear  
- Layout does not break on smaller screens  

---

## 9. Performance

The website is optimized for performance:

- Images are stored locally and properly sized  
- Unused code was removed  
- CSS and JavaScript are organized and efficient  
- No unnecessary libraries are used  
 

---

## 10. Learning Outcomes

Through this project, I learned:

- How to integrate external APIs into a web application  
- How to implement more complex JavaScript logic  
- How to manage application state using localStorage  
- How to improve performance by cleaning unused code  
- How to enhance user experience with interactive features  

---

## 11. Conclusion

This project demonstrates clear improvement from previous assignments by adding advanced functionality and improving user interaction. It shows my ability to work with APIs, manage state, and build more complex front-end features, preparing me for more advanced web development projects in the future.