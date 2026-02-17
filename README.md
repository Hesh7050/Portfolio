# My Portfolio

A personal portfolio website showcasing my projects, skills, education, and experience.

## Features

- **Dark theme** - Dark blue and grey color scheme
- **About Me** - Introduction with profile photo
- **Skills** - Technologies and tools with icons
- **Education** - Academic background and certifications
- **Projects** - Portfolio of work with GitHub links and screenshots
- **Contact** - Message form (delivers to your email via FormSubmit.co) and social links

**Contact form:** Uses FormSubmit.co - messages go to heshhmk@gmail.com. The first time someone submits, FormSubmit will email you an activation link; click it to start receiving messages.

## Setup

1. Open the project in VS Code
2. Edit `index.html` to add your personal details:
   - **Name**: Replace "Your Name" (appears in hero, footer, contact)
   - **About**: Update the bio in the About section
   - **Skills**: Add/remove skill cards - see [Devicons](https://devicon.dev/) for more icons
   - **Education**: Update university names, degrees, years
   - **Projects**: Replace titles, descriptions, GitHub URLs for each project
   - **Contact**: Update email and social media links
3. Add project screenshots to `assets/images/` named `project1.jpg`, `project2.jpg`, `project3.jpg` (or update the `src` in HTML to match your filenames)
4. Your profile photo is already at `assets/profile-photo.png`

## Preview

Open `index.html` in your browser or use a live server extension in VS Code.

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Font Awesome & Devicons for icons

## Push to GitHub

1. Create a new repository on [GitHub](https://github.com/new)
2. Run these commands in your terminal (from the portfolio folder):

```bash
git add .
git commit -m "Initial commit: Personal portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

3. Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and repository name.
