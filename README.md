# PortfolioSite  

##  Project Overview  
This project is my **HTML5 and CSS3 Portfolio Website**, created as part of **Assignment 1**.  
  

##  File Structure  
PortfolioSite/
│
├── index.html # Homepage with intro, recent work, and core skills
├── about.html # About Me page with photo and video
├── projects.html # Projects page showcasing my work
├── contact.html # Contact page
│
├── css/
│ ├── style.css # Base styles and overall theme
│ ├── mobile.css
│ ├── tablet.css
│ └── laptop.css
│
├── images/ # Screenshots and profile picture
├── videos/ # Embedded video files
└── README.md # Documentation


##  Features  
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

##  Responsive Design (Viewport Sizes)  
I created three separate stylesheets to support responsive design:  
- **Mobile (`mobile.css`)** → `max-width: 600px`  
  - Designed for small smartphone screens.  
  - Cards stack vertically and text/images resize for readability.  

- **Tablet (`tablet.css`)** → `601px – 1024px`  
  - Optimized for medium screens such as iPads.  
  - Adjusts spacing, font sizes, and layout margins.  

- **Laptop (`laptop.css`)** → `min-width: 1025px`  
  - Standard desktop layout with centered frosted boxes and wider margins.  

---

## Color Scheme & Gradients  
- **Base Colors**: Emerald green, mint green, golden yellowish accents.  
- **Scheme Type**: green + yellow with accent tones.  
- **Why Chosen**: I thought it looked cool and has a modern tone in it.  
- **Gradients Used**:  
  - **Body Background**: A linear gradient from mint ('#d1fae5') to emerald ('#10b981').  
  - **Highlighted Name**: Gradient text effect using emerald → blue → purple.  

---

##  How to Run  
1. Clone or download the repository  
2. Open `index.html` in your browser  
3. Navigate using the header links (Home | About Me | Projects | Contact)  

Deployed version: [GitHub Pages Link](https://jovalmangalan.github.io/PortfolioSite/)  

---

##  Validation & Testing  
still testing

---

##  External Code Citations  
- Gradient text effect adapted from [MDN Docs on background-clip](https://developer.mozilla.org/en-US/docs/Web/CSS/background-clip).  
- W3C validation and accessibility tools used as required by the assignment.  ~~
- All other code written by me.  
