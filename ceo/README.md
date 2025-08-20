# The CEO Whisperer: Personal Branding for the Ambitious Workshop Website

## Project Overview
Welcome to the official website for **The CEO Whisperer: Personal Branding for the Ambitious**, a transformative workshop hosted by PR Pros Toastmasters. This workshop empowers Toastmasters members and aspiring leaders to elevate their personal brand and executive presence through persuasive communication skills, leveraging the **AIDA model (Attention, Interest, Desire, Action)**. Designed for ambitious professionals, it offers practical strategies to stand out in competitive environments.

This repository contains all files for the workshop’s static website, serving as a central hub for promotional content, detailed agendas, speaker outlines, and resources. The site is built with Toastmasters branding for a professional, cohesive look and is optimized for easy deployment.

## Website Structure
The website includes the following pages:
- **`index.html`**: The landing page, featuring an overview of the workshop, its benefits, testimonials, and a waitlist registration form for attendee sign-ups.
- **`agenda.html`**: A detailed timeline of the workshop sessions, including speeches, interactive activities, and key timings, presented in a visually engaging format.
- **`speakers.html`**: Outlines for each speech, structured using the AIDA model, with clear objectives and descriptions of associated activities.
- **`aida.html`**: An in-depth explanation of the AIDA model, its application in public speaking and personal branding, and real-world examples (e.g., corporate campaigns, TED Talks).
- **`resources.html`**: A curated collection of downloadable checklists, visual guides, templates, recommended books, and links to professional organizations for ongoing personal branding development.

## Features
- **Responsive Design**: Optimized for seamless viewing on desktops, tablets, and mobile devices.
- **Toastmasters Branding**: Incorporates the official Toastmasters color palette (navy blue, gold) and typography for a professional, consistent aesthetic.
- **Engaging Content**: Includes compelling calls to action, detailed session descriptions, and structured information to attract and inform attendees.
- **Interactive Elements**: Features hover effects on cards, subtle fade-in animations on the agenda timeline, and client-side form validation.
- **Netlify Form Integration**: The waitlist form on `index.html` is configured for Netlify Forms, enabling easy collection and management of submissions.

## Technologies Used
- **HTML5**: Provides semantic structure for accessible, organized content.
- **CSS3**: Embedded in each HTML file for self-contained styling, including responsive layouts and Toastmasters branding.
- **JavaScript**: Enables minor interactivity, such as form validation and agenda animations.
- **Font Awesome**: Supplies scalable vector icons for visual enhancement.
- **Google Fonts**: Uses 'Montserrat' for headings and 'Open Sans' for body text, ensuring modern, readable typography.

## Setup and Deployment
This is a static HTML/CSS/JS website, designed for straightforward setup and deployment.

### Clone the Repository
```bash
git clone https://github.com/your-username/the-ceo-whisperer-workshop.git
cd the-ceo-whisperer-workshop
```

### Local Development
- Open any `.html` file (e.g., `index.html`) in a web browser to view the site locally. No server setup is required.
  - **macOS**: `open index.html`
  - **Windows**: `start index.html`
  - **Linux**: `xdg-open index.html`

### Deployment
The website is optimized for deployment on **Netlify** (recommended for form functionality) or **GitHub Pages**.

#### Deploying with Netlify
1. Log in to [Netlify](https://www.netlify.com) and select **Add new site** > **Import an existing project**.
2. Connect to your Git provider (e.g., GitHub) and select the `the-ceo-whisperer-workshop` repository.
3. Configure deployment settings:
   - **Branch to deploy**: `main`
   - **Build command**: Leave empty (static site)
   - **Publish directory**: `.` (root directory)
4. Click **Deploy site**. Netlify will provide a unique URL for your live site.
5. For the waitlist form (`index.html`):
   - Ensure the form includes `data-netlify="true"` and `name="ceo-whisperer-waitlist"`.
   - View submissions in the Netlify dashboard under **Forms**.

#### Deploying with GitHub Pages
1. Push the repository to GitHub.
2. Navigate to **Settings** > **Pages** in the repository.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Access the site at `https://your-username.github.io/the-ceo-whisperer-workshop`.

## Contributing
As a workshop-specific website, direct contributions are not expected, but we welcome suggestions for improvements. To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make changes (e.g., fix bugs, enhance design).
4. Commit changes:
   ```bash
   git commit -m 'Add new feature'
   ```
5. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a Pull Request with a detailed description.
7. Report issues or suggestions via the repository’s **Issues** tab.

## Contact
For questions about the workshop or PR Pros Toastmasters, visit our official website: [https://prpros.toastmastersclubs.org/](https://prpros.toastmastersclubs.org/).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.