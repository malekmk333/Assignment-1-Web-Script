# Malik Khan – Personal Portfolio Website (Assignment 1)

## 1. Overview
This is my personal portfolio website consisting of **4 pages**:  
1. **Home** – Introduction to the portfolio website and letting user know about the navigation tab above.
2. **About Me** – Personal introduction, image of myself, and introductory video that has a poster.
3. **Projects** – Summary of 4 projects I have worked on.
4. **Contact Me** – Contact form with validation. 

This website demonstrates **responsive design**, **semantic HTML**, **separate CSS for mobile, tablet, and desktop**, and **basic UI styling**.


## 2. File Structure
Assignment-1-Web-Script/
│
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│ ├── base.css
│ ├── desktop.css
│ ├── tablet.css
│ └── mobile.css
├── Images/
│ ├── aboutmeimg.jpg
│ ├── logopic.png
│ └── poster.jpg
└── Videos/
├── AboutMeVid.mp4
└── AboutMeVid.ogv



## 3. Code Sources & Documentation
- All code used is **self-written**, inspired by **course lectures and HTML/CSS examples**, and some **online resources I used when running into certain challenges which i will list below**.  
- CSS reset and why it is used (https://stackoverflow.com/questions/11578819/css-reset-what-exactly-does-it-do)
- Linear-gradient and how to use it (https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient#:~:text=The%20linear%2Dgradient()%20CSS%20function%20creates%20an%20image,or%20more%20colors%20along%20a%20straight%20line.)
- How to edit video box size (https://www.w3schools.com/Css/css_rwd_videos.asp)


## 4.Responsive design 
- Each viewport(Mobile, Desktop, Tablet) has it's own css file to adjust layout, images, and video sizes. 
- For mobile I used max width: 600px. Project boxes, Videos, Images, Forms & Buttons, all set with percentages because they enable elements to adapt fluidly to varying screens and orientations. 
- For tablet min-width is 601px and max-width 900px. Project boxes, Videos, and Images all set with percentages aswell.
- For desktop, min width is 901 px. Project boxes, Videos, and Images all set with px(pixels) due to their predictable and consistent behaviour in defining fixed-size elements. 
- Sources used: (https://stackoverflow.com/questions/19933143/css-media-queries-pixel-density-desktop-and-mobile-devices), (https://thewhitelabelagency.com/recommended-screen-resolution-for-web-design/), and some lectures. 

## 5.Linear Gradient Usage
- Applied in header and footer section for all pages. 
- Created a subtle angled gradient from navy to skyblue for the header and the opposite for the footer. 
## For the header 
.header {
    background: linear-gradient(135deg, navy, skyblue);
}
## For the footer
#myportfoliofooter {
    background: linear-gradient(315deg, navy, skyblue);
}

## 6. Color scheme
Colours were based on my logo.
## Primary color: Navy (#000080)
## Secondary Color: Skyblue (#87CEEB)
## Highlight / Hover: Goldenrod (#DAA520)
## Background color for everywhere except project boxes: White (#FFFFFF)
## Background color for project boxes: Navy (#000080)

## 7. Projects Section
Project boxes are inline-block to align horizontally.

Box height adapts slightly to text content, maintaining a consistent layout.

Projects include:

Vehicle Safety Detection System (Python, AI, LiDAR)

Growing Annuity Calculator (VBA Excel)

Healthcare Appointment System (Python Tkinter)

ERPSIM Business Simulation (Power BI, Enterprise Operations)

## 8. Content Form Validation
Name: Required

Email: Required, must be valid email format

Phone: 10-digit number only (pattern="[0-9]{10}")

Comments: Required

## 9.Clone the repository

1. Clone the repository: git clone https://github.com/malekmk333/Assignment-1-Web-Script.git


2. Open any HTML file in a web browser.

3. Test responsiveness by resizing the browser or opening on different devices.
