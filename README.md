Personal Portfolio Website - Nikesh

Live Demo
👉 https://nikesh-protfolio.netlify.app/

Overview
This is a modern, responsive personal portfolio website built with React and Vite. The portfolio showcases Nikesh's projects, skills, and professional information with a clean, minimalist design featuring smooth animations and a cohesive blue color scheme.

Features
Modern UI/UX Design: Clean, minimalist interface with consistent spacing and typography

Responsive Layout: Works seamlessly on mobile, tablet, and desktop devices

Interactive Animations: Smooth transitions and hover effects using Framer Motion

Project Showcase: Elegant display of GitHub projects with descriptions and tags

Skills Visualization: Animated progress bars for technical skills

Contact Form: Functional form with validation and submission feedback


Technologies Used
Frontend Framework: React

Build Tool: Vite

Styling: Tailwind CSS

Animations: Framer Motion

Icons: React Icons

Deployment: Netlify

Sections
Hero Section

Personal introduction with animated text

Prominent call-to-action buttons

Animated avatar placeholder

Social media links

About Section

Professional background and journey

Key statistics (experience, projects, etc.)

Approach to development and design

Projects Section

Featured projects with descriptions

Technology tags for each project

Links to GitHub repositories and live demos

Responsive grid layout

Skills Section

Categorized technical skills (Frontend, Backend, Tools)

Animated proficiency bars

Additional technologies list with hover effects

Contact Section

Contact information (email, location, phone)

Functional contact form with validation

Social media links

Success message after submission

Installation
To run this project locally, follow these steps:

Clone the repository:

bash
git clone https://github.com/yourusername/nikesh-portfolio.git
Navigate to the project directory:

bash
cd nikesh-portfolio
Install dependencies:

bash
npm install
Start the development server:

bash
npm run dev
Open your browser at:

text
http://localhost:5173
Customization
To personalize this portfolio for your own use:

Update personal information in the relevant sections:

src/sections/Hero.jsx - Update name, title, and description

src/sections/About.jsx - Update bio and statistics

src/sections/Contact.jsx - Update contact details

Add your projects to src/sections/Projects.jsx:

jsx
const projects = [
  {
    title: "Project Title",
    description: "Project description",
    tags: ["React", "Node.js", "MongoDB"],
    githubLink: "https://github.com/yourusername/project",
    liveLink: "https://project-demo.com",
  },
  // Add more projects as needed
];
Update your skills in src/sections/Skills.jsx:

jsx
const categories = [
  {
    name: "Frontend",
    skills: [
      { name: "React", level: 95 },
      // Add more skills
    ]
  },
  // Add more categories
];
To change the color scheme, modify the Tailwind colors in src/index.css:

css
@layer base {
  :root {
    --primary: #0f0f13;
    --secondary: #1a1a23;
    --accent: #64ffda;
    --text: #f0f0f0;
    --text-secondary: #b8b8b8;
  }
}
Deployment
The portfolio is deployed on Netlify. To deploy your own version:

Create a new site on Netlify

Connect your GitHub repository

Set the build command: npm run build

Set the publish directory: dist

Click "Deploy site"

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements:

Fork the repository

Create a new branch (git checkout -b feature/improvement)

Commit your changes (git commit -am 'Add some improvement')

Push to the branch (git push origin feature/improvement)

Create a new Pull Request


Acknowledgements
React for the JavaScript library

Vite for the build tool

Tailwind CSS for styling

Framer Motion for animations

React Icons for icons

Netlify for deployment

