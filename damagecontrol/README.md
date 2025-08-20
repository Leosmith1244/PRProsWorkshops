# Damage Control Dungeon: Survive a PR Apocalypse Workshop Website

## Project Overview
Welcome to the official website for the **Damage Control Dungeon: Survive a PR Apocalypse** workshop, hosted by PR Pros Toastmasters! Scheduled for December 2025, this dynamic 90-minute workshop equips Toastmasters members with persuasive communication skills to navigate public relations crises with *Grace Under Fire*. Leveraging **Toulmin’s Model of Argumentation**, participants learn to spin scandals, craft non-apologies, pivot attention, and win competitive PR battles through four engaging speeches and interactive activities.

This repository contains all files for the workshop’s promotional and informational website, designed with Toastmasters branding for a professional, cohesive look and seamless deployment.

## Features
- **Home Page (`index.html`)**: Introduces the workshop’s objectives, benefits, and theme. Includes a client-side validated registration form for easy sign-ups.
- **Agenda Page (`agenda.html`)**: Presents a detailed, visually engaging 90-minute workshop timeline, covering introductions, speeches, activities, debrief, and club business.
- **Speakers Page (`speakers.html`)**: Details the four core speeches ("Oops to Ovation," "The Non-Apology Apology," "The Distraction Gambit," "PR Thunderdome") with objectives, Toulmin’s Model outlines, and activity descriptions.
- **Toulmin’s Model Page (`toulmins_model.html`)**: Provides an in-depth explanation of Toulmin’s Model of Argumentation, with real-world PR crisis case studies (e.g., Johnson & Johnson, Starbucks, BP) for practical insight.
- **Resources Page (`resources.html`)**: Curates recommended books, articles, tools, and organizations (e.g., PRSA) for ongoing PR learning.
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices, ensuring accessibility for all users.
- **Toastmasters Branding**: Incorporates the official Toastmasters color palette (e.g., navy blue, gold) and typography for a consistent, professional aesthetic.
- **Interactive Elements**: Features form validation, subtle animations, and intuitive navigation for an engaging user experience.

## Technologies Used
- **HTML5**: Structures the website’s content for accessibility and clarity.
- **CSS3**: Styles the site with Toastmasters branding, including responsive layouts and custom designs.
- **Font Awesome**: Provides scalable vector icons for visual enhancement.
- **Google Fonts**: Uses 'Montserrat' (headings) and 'Open Sans' (body text) for modern, readable typography.
- **JavaScript**: Enables client-side interactivity, including form validation and smooth animations.

## Installation
To set up the website locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/pr-pros-workshop.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd pr-pros-workshop
   ```

3. **Open the website**:
   Open `index.html` in a web browser (e.g., Chrome, Firefox). All pages are linked from the home page for easy navigation.

## Usage
This website serves as the central hub for the "Damage Control Dungeon" workshop:
- **Prospective Attendees**: Explore the workshop’s purpose, agenda, speech details, and Toulmin’s Model. Register via the form on the home page.
- **Organizers**: Use the site to promote the event, share detailed schedules, and provide resources for participants.
- **Toastmasters Members**: Access speech outlines and PR resources to prepare for the workshop and enhance their skills.

## Deployment
The website is a static HTML/CSS/JS project, designed for easy deployment on platforms like **Netlify** or **GitHub Pages**.

### Deploying with Netlify
1. Create or log in to a [Netlify account](https://www.netlify.com).
2. Select **Add new site** > **Import an existing project**.
3. Connect to your Git provider (e.g., GitHub) and select the `pr-pros-workshop` repository.
4. Configure deploy settings:
   - **Branch to deploy**: `main`
   - **Build command**: Leave empty (static site, no build required)
   - **Publish directory**: `.` (root directory)
5. Click **Deploy site**. Netlify will generate a unique URL for your live site.

### Deploying with GitHub Pages
1. Push the repository to GitHub.
2. In the repository settings, enable GitHub Pages under the **Pages** section.
3. Set the source to the `main` branch and root directory (`/`).
4. Access the site at `https://your-username.github.io/pr-pros-workshop`.

## Contributing
We welcome contributions to enhance the workshop website! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes (e.g., improve design, fix bugs, add features).
4. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
5. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a Pull Request with a clear description of your changes.

Please report issues or suggest enhancements via the repository’s Issues tab.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.