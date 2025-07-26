# Frontend Trainee Task – Responsive Contact Us Page

## **Table of Contents**

- [Frontend Trainee Task – Responsive Contact Us Page](#frontend-trainee-task--responsive-contact-us-page)
  - [**Table of Contents**](#table-of-contents)
  - [**Objective**](#objective)
  - [**Task Description**](#task-description)
    - [**The design includes**](#the-design-includes)
    - [**Design Source**](#design-source)
  - [**Technologies Used**](#technologies-used)
  - [**Technologies \& Techniques Used**](#technologies--techniques-used)
  - [**Project Highlights**](#project-highlights)
  - [**How to Run the Project**](#how-to-run-the-project)
  - [**Responsive Design**](#responsive-design)
  - [**Project Structure**](#project-structure)
  - [**Responsive Breakpoints**](#responsive-breakpoints)
  - [**Completed Subtasks**](#completed-subtasks)
  - [**Final Note**](#final-note)

## </a>**Objective**
The main objective of this task is to practice building a fully responsive and pixel-perfect "Contact Us" page based on a given Figma design. This includes setting up a project repository, structuring HTML/CSS code properly, implementing responsive design techniques, and handling basic interactivity.

## </a>**Task Description**
We are required to implement a contact page layout using HTML, CSS, and optionally JavaScript (to handle the Side Drawer for mobile design), with a responsive design that adapts to both web and mobile views.

<span><strong>For more information about the task:</strong><a href="FE Trainee First Task.pdf"> Task File</a></span>

### </a>**The design includes**
<ul>
    <li>A top navigation header with links.</li>
    <li>A detailed contact form with fields for company details, contact information, and a file upload.</li>
    <li>A sidebar drawer menu for mobile view that slides in when clicking the menu icon.</li>
    <li>A newsletter subscription input field.</li>
    <li>Pixel-perfect implementation matching the original Figma design.</li>
</ul>

### </a>**Design Source**
[Figma Design Link](https://www.figma.com/design/OM5tJ8OWH102HaB4qcm7JL/Application-Form--Community-?node-id=0-1&p=f&t=clWf3BCAkk81SWFd-0)

## **Technologies Used**
<ul>
    <li>HTML5</li>
    <li>CSS3 (with Media Queries for responsiveness)</li>
    <li>JavaScript (for side drawer interactivity)</li>
    <li>Git for version control</li>
</ul>

## **Technologies & Techniques Used**

* **HTML5**
  Used to structure the layout semantically, including navigation, forms, sections, and headings.

* **CSS3**
  Applied for styling and layout, including:

  * **CSS Grid Layout**: Used to organize the page into a flexible, responsive grid system.
  * **Flexbox**: For aligning elements within sections (like form fields and nav items).
  * **Media Queries**: Implemented multiple breakpoints to ensure responsive behavior across:

    * Desktop
    * Tablet
    * Mobile
  * **Custom Styling for Inputs**: Including focus states, validation messages, and hover effects.
  * **Custom Upload Area**: Styled with dashed borders and icons for file input.

* **JavaScript (Vanilla JS)**
  Used to implement the mobile **side drawer (hamburger menu)** functionality, including:

  * Opening/closing drawer
  * Overlay behavior
  * Closing on click outside or X icon

* **Figma**
  The design was interpreted and implemented as **pixel-perfect** as possible based on the provided [Figma file](https://www.figma.com/design/OM5tJ8OWH102HaB4qcm7JL/Application-Form--Community-?node-id=0-1&p=f&t=clWf3BCAkk81SWFd-0).

* **Git**
  Used for version control and incremental commits throughout the task phases.

## **Project Highlights**

This project demonstrates the following:

* Pixel-perfect conversion from Figma to code.
* Fully responsive layout using **CSS Grid** and **Media Queries**.
* Functional **Side Drawer Navigation** for mobile screens using vanilla JavaScript.
* Custom file upload UI with icons.
* Accessible and validated input fields with error messages.
* Visual consistency across devices.

## **How to Run the Project**

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/frontend-trainee-contact-page.git
   cd frontend-trainee-contact-page
   ```

2. Open `index.html` directly in your browser, or use a local server:

   ```bash
   # Python3
   python3 -m http.server
   ```

3. Make sure the `images` folder is in the correct directory structure.

## **Responsive Design**

The layout adjusts based on screen size:

* **Large Screens (≥ 1260px):** Two-column layout with large paddings and spacious navigation.
* **Medium Screens (900px – 1259px):** Slightly reduced paddings and column spacing.
* **Tablets (770px – 899px):** Navbar hidden, replaced with a hamburger menu. Single-column layout for content.
* **Small Devices (660px – 769px):** Adjusted font sizes and padding in the side drawer and other elements.
* **Extra Small Devices (≤ 430px):** Simplified layout with reduced paddings and font sizes for better readability.
  
## **Project Structure**

```
project/
│
├── index.html             # Main HTML structure for the landing page
├── styles.css             # All global and responsive CSS styles
├── main.js                # JS logic for interactivity (e.g. toggling drawer)
├── assets/                # Static assets: images, icons (menu, upload, flags, etc.)
└── README.md              # This file - Project overview and instructions
```

## **Responsive Breakpoints**

```css
@media (max-width: 1260px)  => laptops
@media (max-width: 900px)   => small laptops / large tablets
@media (max-width: 770px)   => tablets
@media (max-width: 660px)   => small tablets / large phones
@media (max-width: 430px)   => phones
```

## **Completed Subtasks**

* [x] Setup GitHub repository
* [x] Created header with nav links
* [x] Built the contact form layout
* [x] Styled input fields and error messages
* [x] Implemented file upload section
* [x] Added mobile drawer navigation
* [x] Ensured full responsiveness
* [x] Matched design with Figma pixel-by-pixel


## **Final Note**

This project was implemented with a focus on being as close as possible to the original Figma design provided. While some minor adjustments were made for responsiveness and browser consistency, every effort was made to ensure a pixel-perfect result across different screen sizes.