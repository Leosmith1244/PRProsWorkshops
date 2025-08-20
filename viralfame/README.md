# PR Pros Toastmasters: Viral Fame Lab Workshop Website 🚀

## Project Overview
Welcome to the official website for the **Viral Fame Lab: Crack the Code of Explosive Content** workshop, hosted by PR Pros Toastmasters. This dynamic workshop, scheduled for 2025, empowers PR professionals and Toastmasters members to create compelling, viral content using **Aristotle’s Rhetorical Triangle** (Ethos, Pathos, Logos). The site serves as a central hub for workshop information, including a detailed agenda, speaker guides, and an in-depth exploration of the Rhetorical Triangle, all designed to inspire and educate attendees.

This repository contains all files for the workshop’s static website, built with Toastmasters branding for a professional, visually appealing experience and optimized for seamless deployment.

## Features
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices, ensuring accessibility for all users.
- **Intuitive Navigation**: Easy access to Home, Agenda & Timeline, Speakers, and Rhetorical Triangle pages.
- **Compelling Hero Section**: A visually striking introduction to the workshop, highlighting its value and theme.
- **Detailed Agenda & Timeline**: An interactive 90-minute workshop timeline with facilitator cues for smooth execution.
- **Speaker Guides**: Comprehensive outlines for each speech, providing insights and structure for speakers and attendees.
- **Rhetorical Triangle Deep Dive**: An in-depth explanation of Ethos, Pathos, and Logos, with real-world and Toastmasters-specific PR examples.
- **Interactive Registration Form**: A Netlify Forms-ready form on the home page for attendee sign-ups, with client-side validation.
- **Toastmasters Branding**: Incorporates official Toastmasters colors (navy blue, gold) and typography for a cohesive, professional look.
- **Unsplash Images**: High-quality, relevant images enhance visual appeal across the site.

## Getting Started
To get a local copy of the website up and running, follow these simple steps.

### Prerequisites
- A web browser (e.g., Chrome, Firefox, Safari) to view the site locally.
- No server setup or additional software is required for basic viewing.

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/viral-fame-lab-workshop.git
   ```
   (Replace `your-username` with your actual GitHub username)

2. **Navigate to the project directory**:
   ```bash
   cd viral-fame-lab-workshop
   ```

3. **Open the website**:
   - Double-click `index.html` in your file explorer, or open it in a web browser:
     - **macOS**: `open index.html`
     - **Windows**: `start index.html`
     - **Linux**: `xdg-open index.html`

## Deployment (Netlify)
The website is a static HTML/CSS/JS project, configured for easy deployment on **Netlify** (recommended for form functionality) or other platforms like GitHub Pages.

### Deploying with Netlify
1. **Create a GitHub Repository**: Push this project to a new GitHub repository.
2. **Connect to Netlify**:
   - Log in to [Netlify](https://www.netlify.com) or sign up for free.
   - Click **Add new site** > **Import an existing project**.
   - Connect your Git provider (e.g., GitHub) and select the `viral-fame-lab-workshop` repository.
3. **Configure Build Settings**:
   - **Branch to deploy**: `main` (or your default branch)
   - **Build command**: Leave empty (static site)
   - **Publish directory**: `.` (root directory)
   - **Functions directory**: Leave empty (no Netlify Functions used)
4. **Deploy Site**: Click **Deploy site**. Netlify will build and deploy the site, providing a unique URL.
5. **Netlify Forms Setup**:
   - Ensure the registration form in `index.html` includes `data-netlify="true"` and `name="viral-fame-lab-registration"`.
   - View form submissions in the Netlify dashboard under **Forms**.

### Deploying with GitHub Pages
1. Push the repository to GitHub.
2. Navigate to **Settings** > **Pages** in the repository.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Access the site at `https://your-username.github.io/viral-fame-lab-workshop`.

## File Structure
```
viral-fame-lab-workshop/
├── index.html            # Home page with hero section and registration form
├── timeline.html         # Workshop agenda and timeline with facilitator cues
├── speakers.html         # Speaker outlines for workshop speeches
├── rhetorical-triangle.html # Explanation of Aristotle’s Rhetorical Triangle
├── styles.css            # Custom CSS for Toastmasters branding and styling
├── thank-you.html        # Optional: Thank-you page for form submissions
├── README.md             # This README file
```

**Note**: The `thank-you.html` page is optional and serves as the redirect destination for form submissions.

## Contributing
We welcome suggestions to enhance the Viral Fame Lab workshop website! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Make your changes (e.g., improve design, fix bugs, add content).
4. Commit your changes:
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
5. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
6. Open a Pull Request with a clear description of your changes.

Report issues or suggest improvements via the repository’s **Issues** tab.

## License
Distributed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions about the workshop or PR Pros Toastmasters, visit our official website: [https://prpros.toastmastersclubs.org/](https://prpros.toastmastersclubs.org/).