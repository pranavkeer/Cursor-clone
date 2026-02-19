Cursor Clone (Desktop UI Replica)

A pixel-accurate desktop clone of the Cursor homepage built using semantic HTML and modern CSS.

Live Demo:
https://cursor-clone-ncf8.vercel.app/

Overview

This project is a desktop-first UI recreation of the Cursor landing page.
The focus was on layout precision, spacing systems, component structuring, and clean CSS architecture.

Rather than prioritizing responsiveness, this build intentionally focuses on replicating the desktop experience with visual accuracy.

What This Project Demonstrates

Semantic HTML structure

Clean and maintainable CSS organization

Advanced layout using Flexbox

Asset management (SVGs, images, logos)

Visual hierarchy & typography handling

Real-world Git workflow

CI/CD deployment via Vercel

Tech Stack

HTML5

CSS3 (Flexbox-based layout)

Git & GitHub

Vercel (Automatic Deployment)

Key Implementation Details
Structured Layout

Clear container system

Reusable utility classes

Section-based layout separation

Styling Approach

Organized CSS file

Scalable spacing system

Consistent typography hierarchy

Deployment Workflow

GitHub connected to Vercel

Automatic redeployments on push to main

Production-ready live URL

Project Structure
cursor-clone/
├── public/        # Static assets
├── src/           # Styles
├── index.html     # Entry file
├── package.json
└── README.md

Local Setup

Clone the repository:

git clone https://github.com/pranavkeer/Cursor-clone.git


Navigate to project folder:

cd Cursor-clone/cursor-clone


If applicable:

npm install
npm run dev


Or open index.html directly in your browser.

Deployment

This project is deployed using Vercel with GitHub integration.

To deploy updates:

git add .
git commit -m "Update section layout"
git push


Vercel automatically rebuilds and updates the live site.

Scope & Limitations

Desktop view only

No responsive/mobile implementation (yet)

Static front-end implementation (no backend functionality)

Future improvement roadmap:

Add full responsive design

Refactor CSS into component-based architecture

Optimize performance

Improve accessibility (ARIA roles, semantic enhancements)

What I Learned

Through this build, I strengthened my understanding of:

Breaking down real-world UI into structured components

Rebuilding complex layouts from scratch

Managing assets and folder structure

Using Git for version control in production workflow

Deploying projects professionally

Author

Pranav Keer
GitHub: https://github.com/pranavkeer

Live Project: https://cursor-clone-ncf8.vercel.app/

Disclaimer

This is a UI recreation created for educational and portfolio purposes.
All original design and branding belong to Cursor.
