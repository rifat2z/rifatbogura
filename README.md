🚀 Personal Portfolio - Md Rifat Hossen

A modern, responsive, and fully animated personal portfolio website designed to showcase software engineering projects, skills, and professional journey. Built with pure HTML, CSS, and JavaScript.

Portfolio Preview
✨ Features

    🌗 Dark/Light Mode Toggle: Smooth transition between light and dark themes.
    🎨 3D Animations: Floating code symbols in the background and 3D tilt hover effects on cards.
    📱 Fully Responsive: Optimized layout for desktop, tablet, and mobile devices.
    ⚡ Smooth Animations: Fade-in effects on scroll and interactive UI elements.
    📧 Functional Contact Form: Integrated with EmailJS to receive messages directly to email.
    📂 Project Showcase: Dynamic grid layout to display projects with tech stacks and demo links.
    🎓 Timeline View: Visual timeline for education and certifications.

🛠️ Technologies Used

    HTML5: Semantic structure and accessibility.
    CSS3: Flexbox, Grid, CSS Variables, Keyframe Animations, Media Queries.
    JavaScript (Vanilla): DOM manipulation, Intersection Observer API, Event Handling.
    External APIs:
        EmailJS (For contact form)
        FontAwesome (Icons)
        Google Fonts (Poppins & Fira Code)

🚀 Getting Started

To run this project locally, follow these simple steps:

    Clone the repository:

    git clone https://github.com/rifat2z/portfolio.git

    Navigate to the project directory:

    cd portfolio

    Open index.html:Simply double-click the index.html file or open it with your preferred code editor (VS Code) and use the "Live Server" extension.

⚙️ Configuration
Contact Form Setup (EmailJS)

The contact form is configured to send emails using EmailJS. To make it work for you:

    Sign up at EmailJS and get your Public Key.
    Create an Email Service (e.g., Gmail) and an Email Template.
    Update the keys in the index.html file (bottom script section):

// Replace with your own Public Keyemailjs.init({  publicKey: "YOUR_PUBLIC_KEY_HERE", });// Update Service ID and Template ID in the send functionemailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)

 
📸 Project Sections 

     Home: Hero section with introduction and call-to-action buttons.
     About: Personal bio, profile image, and key information.
     Skills: Categorized technical skills (Frontend, Backend, Database, Tools).
     Projects: Featured projects with links to live demos and source code.
     Education: Academic timeline with CGPA and certificates.
     Certificates: Professional certifications and achievements.
     Contact: Contact information and a working message form.
     

📂 Repository Structure 
bash
 
  
 
portfolio/
│
├── index.html       # Main HTML file
├── css/             # (Optional) If you separate CSS later
├── js/              # (Optional) If you separate JS later
├── assets/          # Images and icons
└── README.md        # Project documentation
 
 
 
📝 License 

This project is open source and available under the MIT License . 
👤 Author 

Md Rifat Hossen 

     Role: Aspiring Software Engineer
     Location: Bogura, Bangladesh
     

🔗 Connect with me: 

     GitHub 
     LinkedIn 
     Facebook 
     
