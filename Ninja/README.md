# Storytelling Ninja Workshop Website

## Overview
Welcome to the official website for the **Become a Storytelling Ninja: Make Them Beg for More** workshop, organized by PR Pros Toastmasters Club (#7903656). Scheduled for July 2025, this 90-minute online workshop, hosted via Zoom, equips public relations professionals and Toastmasters members with hypnotic storytelling skills for speeches, pitches, and more. Using **Monroe’s Motivated Sequence**, participants learn to craft compelling narratives that captivate audiences. The site, deployed on Netlify, serves as a central hub for the workshop agenda, speaker outlines, a guide to Monroe’s Motivated Sequence, and valuable resources.

**Live Site**: [Insert Netlify URL here, e.g., https://storytelling-ninja-workshop.netlify.app]  
**Word of the Day**: *Hypnotic* (adjective) – Producing a compelling or mesmerizing effect.  
**Why Unmissable?** You'll weaponize storytelling—for speeches, pitches, and even flirting.

## Features
- **Workshop Agenda**: A detailed 90-minute Toastmasters meeting timeline, including four 6-minute speeches, interactive activities (3–4 minutes each), debriefs (3 minutes each), Table Topics, and club business.
- **Speaker Outlines**: Comprehensive outlines for four speeches ("The Hollywood Hook," "Emotional Espionage," "The Plot Twist Payoff," "Improv Storytelling"), each using Monroe’s Motivated Sequence to teach storytelling techniques.
- **Monroe’s Motivated Sequence Guide**: An in-depth explanation of the persuasive framework (Attention, Need, Satisfaction, Visualization, Action), its role in PR, and three marketing campaign examples (Nike, Dove, Apple).
- **Online Optimization**: Content tailored for Zoom, leveraging chat, breakout rooms, polls, and raise-hand features to engage virtual audiences.
- **Resources**: Links to PR Pros Toastmasters ([https://prpros.toastmastersclubs.org/](https://prpros.toastmastersclubs.org/)), FreeToastHost support ([https://support.toastmastersclubs.org](https://support.toastmastersclubs.org)), and storytelling tools.
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices.
- **Toastmasters Branding**: Uses official Toastmasters colors (navy blue, gold) and typography for a professional look.
- **Interactive Elements**: Includes a Netlify Forms-ready registration form and subtle animations for engagement.

## Repository Structure
```
storytelling-ninja-workshop/
├── index.html            # Main page with workshop agenda and registration form
├── speaker-outlines.html # Page with detailed speech outlines
├── monroe-sequence.html  # Explanation of Monroe’s Motivated Sequence
├── styles.css            # Custom CSS for Toastmasters branding and styling
├── js/
│   └── scripts.js        # JavaScript for interactivity (e.g., Zoom integration, form validation)
├── netlify.toml          # Netlify configuration file
├── README.md             # This README file
```

## Setup Instructions

### Prerequisites
- **Node.js**: Optional, for local development with a server.
- **Git**: To clone and manage the repository.
- **Netlify CLI**: Optional, for local testing and deployment.
- A web browser for viewing the site locally.

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/[your-username]/storytelling-ninja-workshop.git
   cd storytelling-ninja-workshop
   ```
   (Replace `[your-username]` with your actual GitHub username)

2. **Install Dependencies** (optional, for local development):
   ```bash
   npm install
   ```

3. **Run Locally** (optional):
   - Use a local server for a better development experience:
     ```bash
     npm install -g live-server
     live-server
     ```
   - Alternatively, open `index.html` directly in a web browser:
     - **macOS**: `open index.html`
     - **Windows**: `start index.html`
     - **Linux**: `xdg-open index.html`

## Netlify Configuration (netlify.toml)
```toml
[build]
  command = "npm run build"  # Adjust if using a build tool; leave empty for static sites
  publish = "public"         # Directory for static files (adjust if needed)
```

### Deploy to Netlify
1. **Create a GitHub Repository**: Push this project to a new GitHub repository.
2. **Connect to Netlify**:
   - Log in to [Netlify](https://www.netlify.com) or sign up.
   - Click **Add new site** > **Import an existing project**.
   - Connect your Git provider (e.g., GitHub) and select the `storytelling-ninja-workshop` repository.
3. **Configure Build Settings**:
   - **Branch to deploy**: `main`
   - **Build command**: Leave empty (static site)
   - **Publish directory**: `.` (root directory)
4. **Deploy Site**: Click **Deploy site**. Netlify will provide a unique URL.
5. **Netlify Forms Setup**:
   - Ensure the registration form in `index.html` includes `data-netlify="true"` and `name="storytelling-ninja-registration"`.
   - View submissions in the Netlify dashboard under **Forms**.

## Usage
- **Access the Site**: Visit the Netlify URL to explore the workshop content.
- **Navigation**: Use the menu to access the agenda, speaker outlines, Monroe’s Motivated Sequence guide, and resources.
- **Interactivity**: Engage with the registration form, Zoom meeting links, and storytelling practice tools.
- **Updates**: Modify HTML/CSS/JS files and push to GitHub for automatic Netlify updates.

## Workshop Details
- **Date**: July 2025
- **Duration**: 90 minutes
- **Format**: Online via Zoom
- **Content**:
  - **Speeches**: Four 6-minute speeches teaching storytelling techniques:
    - *The Hollywood Hook*: Grabbing attention with powerful openings.
    - *Emotional Espionage*: Engaging audiences through emotional resonance.
    - *The Plot Twist Payoff*: Using surprises to captivate listeners.
    - *Improv Storytelling*: Adapting stories on the fly for impact.
  - **Activities**: Four 3–4-minute interactive activities using Zoom features (chat, polls, breakout rooms).
  - **Debriefs**: Four 3-minute debriefs for participants to share insights.
  - **Toastmasters Elements**: Member Introductions, Table Topics, General Evaluation, Club Business.
- **Objective**: Equip PR professionals and Toastmasters members with storytelling skills for persuasive communication.

## Contributing
We welcome contributions to enhance the workshop website! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make changes and commit:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Create a Pull Request with a detailed description.

Report issues or suggestions via the repository’s **Issues** tab.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- **PR Pros Toastmasters Club**: For hosting the workshop ([https://prpros.toastmastersclubs.org/](https://prpros.toastmastersclubs.org/)).
- **FreeToastHost**: For technical support ([https://support.toastmastersclubs.org](https://support.toastmastersclubs.org)).
- **Netlify**: For hosting the live site.
- **Toastmasters International**: For providing frameworks like Monroe’s Motivated Sequence.

## Contact
For questions or feedback, contact PR Pros Toastmasters via their website ([https://prpros.toastmastersclubs.org/](https://prpros.toastmastersclubs.org/)) or reach out to the repository maintainer at [leo.w.smith@gmail.com](mailto:leo.w.smith@gmail.com).