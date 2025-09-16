Portfolio Website - Developer Portfolio
A Responsive, Dark-Themed Technical Portfolio Showcasing Skills, Projects, and Certifications

Live Demo
🔗 Live URL: https://brianmaina.netlify.app/

✨ Key Features
✅ Modern UI/UX

Dark circuit board theme with animated orange accents

Fully responsive (mobile, tablet, desktop)

CSS-only animations (no JavaScript dependency)

✅ Professional Sections

Skills Matrix: Visual showcase of technical proficiencies

Education Timeline: Interactive JKUAT/High School timeline

Project Gallery: Case studies with live demos

Certifications: Cisco credential display with lightbox

Contact Form: Netlify-powered submissions

✅ Technical Highlights

Pure HTML/CSS (zero JavaScript)

Semantic HTML5 markup

CSS Grid/Flexbox layout

Dynamic hover/scroll effects

🛠 Tech Stack
Category	Technologies Used
Frontend	HTML5, CSS3
Design	CSS Grid, Flexbox
Icons	Font Awesome 6
Fonts	Google Fonts
Hosting	Netlify

📂 Project Structure
portfolio/
├── index.html            # Main entry point
│   └── images/           # Optimized assets
│       ├── profile/      # Portrait shots
│       ├── projects/     # Project screenshots
│       └── certs/        # Certification scans
└── README.md             # This documentation

🚀 Deployment Guide
1. Local Development
# Clone repository
git clone https://github.com/Brianmaina427/My_Portfolio_Website.git
cd portfolio

# Run local server (Python)
python3 -m http.server 8000
# Access at http://localhost:8000

2. Netlify Deployment
Push to GitHub/GitLab
Connect repo to Netlify
Set build command: None (static site)
Set publish directory: /

🎨 Customization Guide
1. Personalize Content
Replace placeholder text in index.html:
2. Add Projects
Add images to assets/images/projects/
3. Modify Styling
Edit CSS variables in :root:
:root {
  --primary: #ff7b00;  /* Brand color */
  --dark: #0a0a0a;     /* Background */
  --circuit: #1a1a1a;  /* Circuit pattern */
}
🔧 Troubleshooting
Issue	Solution
Images not loading	Verify case-sensitive paths in HTML
Form not submitting	Add netlify attribute to <form>
Mobile layout breaks	Check viewport meta tag

📬 Contact
Email: brianmaina427@gmail.com

LinkedIn: https://www.linkedin.com/in/brian-maina-b17a642ab/

GitHub: https://github.com/Brianmaina427<p>
