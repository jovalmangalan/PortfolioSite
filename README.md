# PortfolioSite  

## Project Overview  
This project is my **HTML5 and CSS3 Portfolio Website**, created as part of **Assignment 1**.  

## Features  
- Navigation bar across all pages  
- Frosted glass design using CSS blur + transparency effects  
- **About Me Page** with a profile photo and embedded video  
- **Projects Page** with three showcased projects:  
  - Grade 11: Snake Game (Python + Pygame)  
  - Grade 12: Papi Joe’s Shawarmania (Python + Pygame)  
  - Year 2: Healthcare Appointment App (Python + Tkinter)  
- **Contact Page** with a form that validates name, email, phone, and comments  
- **Responsive Design** with distinct layouts for mobile, tablet, and laptop  

---

## Responsive Design (Viewport Sizes)  
I created three separate stylesheets to support different screen sizes:  
- **Mobile (`mobile.css`)** → `max-width: 600px`  
- **Tablet (`tablet.css`)** → `601px – 1024px`  
- **Laptop (`laptop.css`)** → `min-width: 1025px`  

---

## Color Scheme & Gradients  
- **Base Colors**: Emerald green, mint green, golden yellowish accents  
- **Scheme Type**: Green + yellow with accent tones  
- **Why Chosen**: Modern and fresh aesthetic  
- **Gradients Used**:  
  - **Body Background**: Linear gradient from mint (`#d1fae5`) → emerald (`#10b981`)  
  - **Highlighted Name**: Gradient text effect (emerald → blue → purple)  

---

## How to Run  
1. Clone or download the repository  
2. Open `index.html` in your browser  
3. Navigate using the header links (Home | About Me | Projects | Contact)  

Deployed version: [GitHub Pages Link](https://jovalmangalan.github.io/PortfolioSite/)  

---

## Validation & Testing  
- **HTML Validation**: All `.html` files passed the [W3C Markup Validation Service](https://validator.w3.org/) after fixes. All warnings (e.g., trailing slashes on void elements) were resolved.  
  - ![HTML Validation Screenshot](https://github.com/user-attachments/assets/75a4f807-5bd5-4206-88d6-5d5d57ff860b)

- **CSS Validation**: All stylesheets passed the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).  
  - ![CSS Validation Screenshot](https://github.com/user-attachments/assets/ce705ec5-d668-4385-8027-cb6215b8e298)

- **Accessibility Testing**:  
  - Checked with [WAVE Web Accessibility Tool](https://wave.webaim.org/).  
  - Contrast on button issue fixed.  
  - ![WAVE Accessibility Screenshot](https://github.com/user-attachments/assets/0d269c2c-b12d-4093-975a-075e38b26073)

- **Link Validation**:  
  - Tested with the [W3C Link Checker](https://validator.w3.org/checklink).  
  - All internal and external links passed.  
  - **Note:** The only issue flagged was with the `mailto:` link (`mailto:Joval.mangalan@ontariotechu.net`). This is expected since the Link Checker disables `mailto:` links by default — the email link works correctly in browsers.  
  - ![Link Checker Screenshot](https://github.com/user-attachments/assets/c6ecc8ac-bc54-47f3-9a56-e3ba4c19ff98)



## External Code Citations  
- **Gradient Text Effect (Name Highlight)**: Adapted from [CSS-Tricks – Gradient Text](https://css-tricks.com/gradient-text/) 
- **Frosted Glass Effect (Glassmorphism)**: Inspired by [CSS-Tricks – Frosting Glass with CSS Filters](https://css-tricks.com/frosting-glass-css-filters/)
- All other HTML, CSS, and content written by me.  
