# Prodesk IT — Digital Marketing Landing Page

A professional and responsive landing page developed for **Prodesk IT's Digital Marketing wing** as part of the Week 1 Sprint 01 internship assignment.

The project demonstrates responsive frontend architecture, CSS fundamentals, JavaScript-based interactions, dark/light theme support, Tailwind CSS migration, accessibility considerations, and deployment using Vercel.

---

## 🚀 Live Demo

**Live Website:**
https://production-phasethree.vercel.app/

---

## 📸 Project Screenshot

<img width="1004" height="497" alt="Screenshot 2026-09-29 221606" src="https://github.com/user-attachments/assets/c06c00d6-5b1b-4cbc-b882-67f9865d506b" />

header section
<img width="1898" height="910" alt="Screenshot 2026-09-29 223143" src="https://github.com/user-attachments/assets/51bd2c19-5e53-4aac-9a44-f8c197195287" />
body section
<img width="1895" height="724" alt="Screenshot 2026-09-29 223202" src="https://github.com/user-attachments/assets/0e25625e-d3e2-441d-82f2-ea02157f772f" />
<img width="1897" height="911" alt="Screenshot 2026-09-29 223229" src="https://github.com/user-attachments/assets/629d7ff5-b121-4cc7-afaa-94c7e50ddc7f" />
<img width="1899" height="906" alt="Screenshot 2026-09-29 223250" src="https://github.com/user-attachments/assets/dc04e9de-22d5-44a0-b5f0-16388f44f638" />
<img width="1898" height="912" alt="Screenshot 2026-09-29 223305" src="https://github.com/user-attachments/assets/2c39f842-e1c8-4eaf-8c85-8eff31f729b4" />
<img width="1901" height="905" alt="Screenshot 2026-09-29 223321" src="https://github.com/user-attachments/assets/ac89bb98-8cce-4966-8509-12ae675164c1" />
footer section
<img width="1893" height="905" alt="Screenshot 2026-09-29 223332" src="https://github.com/user-attachments/assets/6c13f4a0-8755-49b7-b85b-39933b0bc503" />









# 📋 Sprint Objective

The objective of this sprint was to build and deploy a professional landing page module for **Prodesk IT** while demonstrating strong frontend fundamentals.

The project was developed in three phases:

* **Phase 1 — Base MVP**
* **Phase 2 — UI/UX Enhancements**
* **Phase 3 — Stretch Goals & Optimization**

---

# 🏗️ Phase 1 — Base MVP

Phase 1 was implemented using **HTML5 and raw CSS**, following the sprint requirement that UI frameworks such as Bootstrap and Tailwind CSS must not be used for the initial MVP.

### Features

* Responsive Navbar
* Company logo
* Navigation links

  * Home
  * About
  * Services
  * Contact
* Mobile responsive navigation
* Hero section
* Primary "Get Started" CTA
* Services section
* Three service cards
* Responsive layout using CSS Flexbox/Grid
* Footer
* Social media links/icons
* Responsive desktop and mobile layouts

### Architecture

The Phase 1 styling was implemented using:

* CSS Flexbox
* CSS Grid
* Media Queries
* CSS transitions
* Responsive units
* Semantic HTML

---

# 🌙 Phase 2 — UI/UX Enhancements

Phase 2 focused on improving the interaction and usability of the landing page.

### Features

### Dark / Light Theme

A theme controller was implemented using vanilla JavaScript.

The theme state is applied to the page and allows users to switch between:

* Light Mode
* Dark Mode

### Micro-interactions

Interactive hover effects were added to:

* CTA buttons
* Navigation elements
* Service cards

Service cards use transform and transition effects to create a lifting effect on hover.

### Sticky Navigation

The navigation bar remains visible while scrolling through the page.

---

# ⚡ Phase 3 — Tailwind CSS Migration

Phase 3 migrated the styling architecture from standard CSS toward **Tailwind CSS**.

The project uses **Tailwind CSS v4.3.3** with the Tailwind CLI.

### Tailwind Configuration

The project uses:

```json
{
  "scripts": {
    "build": "npx @tailwindcss/cli -i ./src/input.css -o ./dist/output.css --minify",
    "watch": "npx @tailwindcss/cli -i ./src/input.css -o ./dist/output.css --watch"
  }
}
```

### Build

To generate the production CSS:

```bash
npm install
npm run build
```

For development with automatic CSS rebuilding:

```bash
npm run watch
```

Generated CSS:

```text
dist/output.css
```

---

# 🧊 Glassmorphism

The sticky navigation uses a frosted-glass style effect using CSS properties such as:

```css
backdrop-filter
```

This provides a translucent navigation surface while scrolling.

---

# 📱 Responsive Design

The website was designed to work across different viewport sizes.

### Tested layouts

* Desktop
* Laptop
* Tablet
* Mobile

The layout adapts using responsive CSS and Tailwind utilities.

---

# ♿ Accessibility

Accessibility considerations include:

* Semantic HTML elements
* Descriptive image `alt` attributes
* Keyboard-friendly interactive elements
* Appropriate color contrast
* Responsive text sizing
* Reduced-motion support

The project also includes:

```css
@media (prefers-reduced-motion: reduce)
```

to reduce animations for users who prefer reduced motion.

---

# 🛠️ Technologies Used

| Technology   | Purpose                        |
| ------------ | ------------------------------ |
| HTML5        | Page structure                 |
| CSS3         | Layout and styling             |
| Flexbox      | Component alignment            |
| CSS Grid     | Service/card layouts           |
| JavaScript   | Interactions and theme control |
| Tailwind CSS | Phase 3 styling architecture   |
| Git          | Version control                |
| GitHub       | Source code hosting            |
| Vercel       | Deployment                     |

---

# 📁 Project Structure

```text
prodesk-phase-three/
│
├── images/
│   ├── prodesk.png
│   └── Screenshot 2026-09-27 102006.png
│
├── src/
│   └── input.css
│
├── dist/
│   └── output.css
│
├── index.html
├── script.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

# ⚙️ Local Development

Clone the repository:

```bash
git clone https://github.com/amlesh807699/[YOUR-REPOSITORY].git
```

Move into the project:

```bash
cd [YOUR-REPOSITORY]
```

Install dependencies:

```bash
npm install
```

Build Tailwind CSS:

```bash
npm run build
```

For development:

```bash
npm run watch
```

Then open:

```text
index.html
```

in the browser or use VS Code Live Server.

---

# 🚀 Deployment

The project is deployed using **Vercel**.

Deployment workflow:

```text
Local Development
       ↓
Git
       ↓
GitHub
       ↓
Vercel
       ↓
Production Website
```

The project uses the following Vercel configuration:

```text
Root Directory: .
Build Command: npm run build
Output Directory: .
Install Command: npm install
```

---

# 🧪 QA & Testing

The website was tested for:

* Responsive layout
* Navigation functionality
* Dark/light theme
* CTA interactions
* Service card hover effects
* Image loading
* Favicon loading
* Mobile viewport
* Desktop viewport
* CSS generation
* Production deployment

---

# 📊 Performance & Accessibility

Google Lighthouse was used to evaluate:

* Performance
* Accessibility
* Best Practices
* SEO

### Lighthouse Results

| Category       |       Score |
| -------------- | ----------: |
| Performance    | [Add Score] |
| Accessibility  | [Add Score] |
| Best Practices | [Add Score] |
| SEO            | [Add Score] |

> Replace the scores above with your actual Lighthouse results after running the audit.

---

# 🎥 QA Demonstration

A short functional demonstration video was recorded showing:

1. Desktop rendering
2. Mobile responsive rendering
3. Dark/light theme
4. Navigation
5. Service cards
6. Project structure

**QA Video:**
[Add your video link here]

---

# 🤖 AI Usage

AI assistance was used during development for:

* Understanding CSS concepts
* Debugging frontend issues
* Understanding Tailwind CSS
* Git/GitHub troubleshooting
* Deployment troubleshooting
* Code explanation and learning

All AI prompts used during development are documented separately in:

```text
Prompts.md
```

The generated code was reviewed, understood, tested, and modified during development.

---

# 📌 Sprint Deliverables

| Deliverable             | Status |
| ----------------------- | ------ |
| Responsive Landing Page | ✅      |
| Navbar                  | ✅      |
| Hero Section            | ✅      |
| Services Section        | ✅      |
| Footer                  | ✅      |
| Dark/Light Mode         | ✅      |
| Micro-interactions      | ✅      |
| Sticky Navigation       | ✅      |
| Tailwind CSS Migration  | ✅      |
| GitHub Repository       | ✅      |
| Vercel Deployment       | ✅      |
| README.md               | ✅      |
| Prompts.md              | ✅      |
| QA Video                | 🔄     |
| Lighthouse Audit        | 🔄     |

---

# 👨‍💻 Developer

**Amlesh Kumar**

Frontend Developer Intern
Prodesk IT

GitHub:
https://github.com/amlesh807699

---

# 📄 License

This project was created as part of the Prodesk IT internship sprint assignment.
