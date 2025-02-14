Software Design Document
Project Title: Collin Flack Portfolio Website
 Version: 1.0
 Date: February 13, 2025
 Author: Collin Flack
Table of Contents
1. Introduction


2. System Overview


3. Scope and Objectives


4. Functional Requirements


5. Non-functional Requirements


6. System Architecture


7. Detailed Design


8. User Interface Design


9. Testing and Validation


10. Deployment and Maintenance


11. Future Enhancements


12. Appendices






1. Introduction
Purpose of the Document:
 This SDD is intended to clarify the design and technical aspects for developing a modern, aesthetic, and fully functioning portfolio website. It serves as a single source of truth for all stakeholders, facilitating communication, collaboration, and future expansions.
Intended Audience:
Development and design teams


Stakeholders and project reviewers


Future collaborators seeking to extend or refine the application


Project Overview:
 The portfolio website is designed to showcase professional projects, technical skills, and background information. Drawing from a rich history in computer science and web development, the site will feature multiple pages with unique content areas while maintaining a unified visual identity.
Goals and Objectives:
Present work and projects in a clear, engaging manner


Reflect professionalism through a clean, responsive design


Implement a consistent color palette and typography throughout


Allow for future integration of dynamic elements and content updates






2. System Overview
The system is a multi-page static website built using HTML5 and CSS3. The site consists of four main pages:
Home: A hero section that introduces the professional profile and includes a call-to-action.


Projects: A grid-based layout displaying project cards with descriptions and links.


About: An overview of your background, technical skills, and professional highlights.


Contact: A form for visitors to send messages directly.


Each page reuses a common header and footer, ensuring consistency throughout. The design uses a unified color palette (e.g., #FFDAB3, #C8AAAA, #9F8383, #574964) that delivers an aesthetic and polished look.









3. Scope and Objectives
Scope:
Develop a professional portfolio website that is static, responsive, and accessible.


Showcase multiple content types such as project details, skill lists, biographical information, and a contact form.


Use a pre-defined color palette and modern design practices to create visual cohesion.


Objectives:
Deliver a website that reflects your extensive background and technical prowess.


Simplify navigation so that users can easily explore different sections.


Future-proof the design for possible dynamic enhancements (e.g., animations, dark mode).










4. Functional Requirements
Navigation:


A consistent header navigation bar linking to all pages.


Visual indication (e.g., active link styling) for the current page.


Home Page:


A hero section with your name, a brief description, and a call-to-action button linking to the Projects page.


Projects Page:


A grid or card layout that displays multiple project entries.


Each project card features an image, project title, brief description, and a “Learn More” link.


About Page:


A two-column layout featuring a profile image and biographical text.


Lists of technical skills and professional highlights.


Contact Page:


A contact form with fields for name, email, and message.


Basic form validation to ensure required fields are completed before submission.






5. Non-functional Requirements
Design Consistency:


Uniform application of the provided color palette and typography.


Reusable components such as header, footer, and buttons.


Responsiveness and Browser Compatibility:


The layout must be responsive across desktops, tablets, and mobile devices.


Compatibility with modern browsers (Chrome, Firefox, Edge, Safari).


Performance:


Optimized assets (images, CSS) to ensure fast load times.


Minimalistic design for a smooth user experience.


Accessibility:


Semantic HTML and proper labeling to support users with disabilities.


Ensure color contrast meets accessibility standards.








6. System Architecture
Technology Stack:
Frontend: HTML5, CSS3


Optional Enhancements: JavaScript may be integrated in future versions for dynamic content or interactive elements.


File Structure Overview:
text
portfolio/
├── index.html
├── projects.html
├── about.html
├── contact.html
├── css/
│   └── style.css
└── images/
    ├── profile.jpg
    ├── project1.jpg
    ├── project2.jpg
    └── project3.jpg

Component Diagram (Conceptual):
Header Component: Contains navigation links.


Footer Component: Displays copyright.


Content Sections: Each page contains a main section dedicated to its content (hero, projects grid, about details, contact form).




7. Detailed Design
Page Designs:
Home (index.html):


Contains a full-width hero section with engaging typography.


Features a call-to-action button prompting visitors to explore projects.


Projects (projects.html):


Utilizes a CSS Grid layout to arrange project cards.


Each card shows an image, title, description, and a link to more details.


About (about.html):


A split layout with a profile image and text blocks describing your background and technical skills.


Two sections of skill lists: one for technical skills and one for professional highlights.


Contact (contact.html):


A straightforward form with labeled input fields.


The form layout is designed for clarity, with sufficient spacing and user-friendly controls.


Code Reuse:
 Common elements such as navigation and footer are repeated across pages for design consistency. The CSS file (css/style.css) centralizes all styling.



8. User Interface Design
Color Palette & Typography:


Primary background color: #FFDAB3


Accent colors: #C8AAAA, #9F8383, #574964


Consistent font choices and sizes to maintain hierarchy (e.g., headings, body text).


Visual Elements:


Use of high-quality images for projects and the profile.


Buttons and links with hover effects for improved interactivity.


Clean, minimalistic style that emphasizes content and clarity.


Layout & Responsiveness:


A fluid grid system that adjusts layouts based on screen size.


Flexbox and CSS Grid ensure that content is well-organized on all devices.








9. Testing and Validation
Browser Testing:


Test across major modern browsers for layout consistency and performance.


Responsive Testing:


Simulate different device sizes (mobile, tablet, desktop) to ensure responsiveness.


Functional Testing:


Verify navigation links, contact form validation, and interactive elements.


Accessibility Testing:


Use accessibility tools to check semantic elements, color contrast, and keyboard navigation.










10. Deployment and Maintenance
Deployment:


The website can be hosted on a static hosting platform (e.g., GitHub Pages, Netlify).


Asset optimization and caching strategies will ensure quick load times.


Maintenance:


Updates to content can be easily made by modifying HTML/CSS files.


Version control (e.g., via Git) should be used to track changes and collaborate on future enhancements.












11. Future Enhancements
Dynamic Enhancements:


Integrate JavaScript for animations, dynamic loading of projects, and form submission handling.


Dark Mode Toggle:


Implement a dark mode to complement the existing color scheme.


Enhanced Accessibility:


Further refine ARIA attributes and semantic HTML based on user feedback.


Content Expansion:


Consider adding a blog section or interactive project demos.


Backend Integration:


Incorporate a CMS or contact form backend to handle form submissions more robustly.









12. Appendices
A. Code Samples:
 Refer to the complete implementations of the HTML/CSS pages provided in earlier documents. The file structure is as follows:
text
portfolio/
├── index.html
├── projects.html
├── about.html
├── contact.html
├── css/
│   └── style.css
└── images/
    ├── profile.jpg
    ├── project1.jpg
    ├── project2.jpg
    └── project3.jpg

B. Style References:
 The CSS file (css/style.css) applies the chosen color palette and layout rules across all pages. Consistent use of color and spacing is maintained throughout the design.

