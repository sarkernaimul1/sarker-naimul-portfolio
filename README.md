# Naimul Sarker — Personal Portfolio Website

## 📁 File Structure
```
portfolio/
├── index.html        ← Main webpage
├── style.css         ← All styling
├── script.js         ← Animations & interactions
├── assets/
│   ├── images/       ← Add your profile photo as "profile.jpg"
│   └── cv/           ← Add your CV as "Naimul_Sarker_CV.pdf"
└── README.md
```

## 🚀 How to Use

### 1. Edit Your Info
Open `index.html` and update:
- Email, Phone, LinkedIn, GitHub links
- Contact form action (see FormSpree below)
- Reference/certification details

### 2. Add Your Photo
- Place your photo in `assets/images/profile.jpg`
- In `index.html`, replace the `.profile-placeholder` div with:
  `<img src="assets/images/profile.jpg" alt="Naimul Sarker" />`

### 3. Add Your CV
- Place your CV as `assets/cv/Naimul_Sarker_CV.pdf`

### 4. Set Up Contact Form (Free)
- Go to https://formspree.io → Create free account
- Create a form → Copy your form ID
- In `index.html`, change:  `<form class="contact-form" id="contactForm">`  
  to:  `<form class="contact-form" id="contactForm" action="https://formspree.io/f/YOUR_ID" method="POST">`
- Remove the `e.preventDefault()` in script.js (or keep for AJAX)

## 🌐 Deploy Free on GitHub Pages

1. Create a GitHub account at github.com
2. Create a new repository named: `naimulsarker.github.io`
3. Upload all files
4. Go to Settings → Pages → Source: main branch
5. Your site goes live at: `https://naimulsarker.github.io`

## 🎨 Customization

### Change Colors
In `style.css`, edit the `:root` variables:
```css
--accent:  #38bdf8;   /* Cyan blue — main accent */
--accent2: #f0a500;   /* Gold — secondary accent */
--bg:      #050d1a;   /* Dark navy background */
```

### Add More Projects
Copy a `.project-card` block in `index.html` and update the content.

### Add Certifications
Update the Achievements section in `index.html`.

## 📱 Features
- Fully responsive (mobile, tablet, desktop)
- Custom animated cursor
- Typing text animation
- Scroll reveal animations
- Skill bar animations
- 3D card tilt effect
- Smooth scrolling navigation
- Contact form with success feedback
- Dark luxury theme with cyan/gold accents
