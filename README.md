# PR Pros Monthly Sessions Portal

## Overview
The PR Pros Toastmasters Monthly Sessions Portal is a centralized website for accessing specialized workshop sessions. It provides a navigable hub for Toastmasters members and guests to explore workshop details, with each workshop having its own dedicated page.

## Table of Contents
- [Project Overview](#project-overview)
- [Website Structure](#website-structure)
- [Adding a New Workshop](#adding-a-new-workshop)
- [Deployment](#deployment)
- [Contact](#contact)

## Project Overview
This portal consolidates PR Pros Toastmasters monthly workshops into a single website. The main `index.html` serves as the entry point, linking to individual workshop pages housed in separate folders. Each workshop page has its own HTML, CSS, and assets for independent design and content.

## Website Structure
The repository is organized for clarity and maintainability:

```
pr-pros-workshops/
├── index.html                  # Main landing page for all workshops
├── ninja/
│   ├── index.html              # "Become a Storytelling Ninja" workshop page
│   └── styles.css              # Styles specific to the Ninja workshop
│   └── ... (other assets)
├── ceo/
│   ├── index.html              # "The CEO Whisperer" workshop page
│   └── styles.css              # Styles specific to the CEO workshop
│   └── ... (other assets)
├── viralfame/
│   ├── index.html              # "Viral Fame Lab" workshop page
│   └── styles.css              # Styles specific to the Viral Fame workshop
│   └── ... (other assets)
└── damagecontrol/
    ├── index.html              # "Damage Control Dungeon" workshop page
    └── styles.css              # Styles specific to the Damage Control workshop
    └── ... (other assets)
```

- **index.html** (root): Main entry point with embedded styles and links to workshop pages.
- **Workshop Folders** (`ninja/`, `ceo/`, `viralfame/`, `damagecontrol/`): Each contains:
  - `index.html`: HTML content for the specific workshop.
  - `styles.css`: Custom CSS for the workshop page.
  - Other assets (e.g., images, JavaScript) specific to the workshop.

## Adding a New Workshop
To integrate a new workshop:

1. **Create a New Folder**:
   ```bash
   mkdir newworkshop
   ```

2. **Place Workshop Files**:
   ```
   newworkshop/
   ├── index.html
   └── styles.css
   └── (other assets)
   ```

3. **Update Main `index.html`**:
   - Open `index.html` in the root directory.
   - Locate the `<section class="workshop-grid container">` block.
   - Add a new `<a>` tag with the `workshop-card` class:
     ```html
     <a href="newworkshop/index.html" class="workshop-card">
         <div class="card-icon"><i class="fas fa-magic"></i></div>
         <h2>New Workshop Title Here</h2>
         <p>A brief, engaging description of what participants will learn in this session.</p>
         <span class="card-date">Month Day, Year</span>
         <button class="btn">Learn More <i class="fas fa-arrow-right"></i></button>
     </a>
     ```
   - Update the `href`, icon, title, description, and date.

4. **Test Locally**:
   - Open `index.html` in a browser to verify all links, especially the new one, work correctly.

## Deployment
The site uses standard HTML, CSS, and JavaScript, making it compatible with static hosting platforms:
- **GitHub Pages**: Push to GitHub and enable Pages in repository settings.
- **Netlify**: Connect your repository for continuous deployment.
- **Vercel**: Host via Vercel’s static site hosting.
- **Traditional Hosting**: Upload files via FTP, ensuring `index.html` is the entry point.

## Contact
For questions or contributions, contact the PR Pros Toastmasters Club leadership.