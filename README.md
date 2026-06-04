# Personal Portfolio — HIRWA KARAMBIZI Kevin

A modern, responsive single-page portfolio showcasing your software engineering work, skills, and experience.

## Getting Started

1. **View the Portfolio**: Open `index.html` in your web browser
2. **No build process required** — this is a static HTML/CSS/JavaScript site

## Features

- ✅ Clean, professional design with dark mode aesthetic
- ✅ Single-page app with smooth section navigation
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Circular profile photo display
- ✅ Organized skills by category (Frontend, Backend, DevOps)
- ✅ Detailed project showcase with tech stack
- ✅ Social accounts and contact section
- ✅ Smooth page transitions and active nav states

## Customization Guide

### 1. Update Your Personal Information

**In `index.html`**, find and replace:
- `HIRWA KARAMBIZI Kevin` — your full name
- `hirwa@example.com` — your email address
- `+1 (234) 567-8900` — your phone number

### 2. Update Your Profile Photo

Replace `unnamed.jpg` with your own photo. The image should be a square photo (at least 320×320 pixels recommended).

### 3. Customize Your Skills

Find the Skills section in `index.html` and update:
- **Frontend skills** — add/remove technologies you use
- **Backend skills** — list your server-side expertise
- **DevOps & Tools** — include deployment, CI/CD, and other tools

Example:
```html
<li>Your Skill Here</li>
```

### 4. Add Your Projects

Replace the sample projects with your own. Each project card includes:
- **Project Title**
- **Tech Stack** (comma-separated technologies)
- **Description** (2-3 sentences about the project)
- **Links** (Live demo and code repository)

Example project card structure:
```html
<article class="card">
    <h4>Your Project Name</h4>
    <p><strong>Tech:</strong> React, Node.js, MongoDB</p>
    <p>Description of what you built, key features, and impact.</p>
    <p class="card-links"><a href="#">Live Demo</a> · <a href="#">View Code</a></p>
</article>
```

### 5. Update About Me Section

Customize the "About Me" section to reflect your experience, interests, and professional goals.

### 6. Update Your Accounts

In the **Accounts section**, update links to your:
- GitHub profile
- LinkedIn profile
- Email address

Replace placeholder URLs with your actual social profiles:
```html
<a href="https://github.com/yourusername" target="_blank" rel="noopener" class="account-card">
```

### 7. Update the Hero Introduction

Customize the hero section headline and description to match your professional brand and goals.

## File Structure

```
Hirwa/
├── index.html          # Main portfolio page (single-page app)
├── style.css           # All styling
├── unnamed.jpg         # Your profile photo
├── README.md           # This file
└── [Other HTML files]  # (Legacy - can be ignored for single-page app)
```

## Section Navigation

The portfolio uses smooth page transitions:
- **Home** — Landing section with introduction and photo
- **About** — Your professional background
- **Skills** — Organized by Frontend, Backend, and DevOps
- **Projects** — Showcase of your work with tech stacks
- **Accounts** — Links to GitHub, LinkedIn, and email
- **Contact** — Contact information and response time

## Browser Support

Works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile: iOS Safari, Chrome Mobile, Firefox Mobile

## Deployment

### Option 1: GitHub Pages (Recommended)
1. Create a GitHub repository
2. Push these files to the repository
3. Go to Settings → Pages → Source: main branch
4. Your portfolio will be live at `yourusername.github.io/portfolio`

### Option 2: Netlify
1. Connect your GitHub repository
2. Build settings: Leave empty (static site)
3. Deploy

### Option 3: Traditional Hosting
Upload all files to your web hosting provider via FTP/SFTP.

## Customization Tips

- **Colors**: Update CSS variables in `style.css` (--accent, --muted, etc.) to match your brand
- **Fonts**: The portfolio uses "Inter" font from Google Fonts
- **Spacing**: Adjust padding/margins in `style.css` for different layouts
- **Add more projects**: Duplicate the card HTML and fill in your details

## License

Feel free to use this portfolio template for your own professional use.

## Questions?

Refer to the inline HTML comments in `index.html` for specific sections you want to modify.
