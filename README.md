# Developer Portfolio Website

A clean, minimalist portfolio website inspired by Jekyll themes for GitHub Pages. Features a responsive design with a left sidebar for developer details and a main content area for CV, projects, and blog sections.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Clean Layout**: 20% left sidebar with developer details, 80% main content area
- **Navigation**: Centered top navigation with Home, Projects, and Blog sections
- **Modern UI**: Inspired by Jekyll themes with clean typography and subtle animations
- **Interactive Elements**: Hover effects, smooth transitions, and scroll-to-top functionality
- **Professional CV Section**: Detailed experience, education, and certifications
- **Projects Showcase**: Grid layout for displaying portfolio projects
- **Blog Section**: Clean layout for blog posts with metadata

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Quick Start

1. **Clone or download** the files to your local machine
2. **Open `index.html`** in your web browser
3. **Customize** the content to match your personal information

## Customization Guidejhgfg

### Personal Information

Edit the following sections in `index.html`:

#### Profile Section (Sidebar)
```html
<!-- Update these elements in the sidebar -->
<h1 class="name">Your Name</h1>
<p class="title">Your Title</p>
<p class="bio">Your bio description</p>
```

#### Contact Information
```html
<!-- Update contact details -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fab fa-github"></i>
    <span>github.com/yourusername</span>
</div>
```

#### Skills
```html
<!-- Update skills in the skills-grid -->
<div class="skills-grid">
    <span class="skill-tag">Your Skill 1</span>
    <span class="skill-tag">Your Skill 2</span>
    <!-- Add more skills as needed -->
</div>
```

### Professional Experience

Update the experience section in the CV area:

```html
<div class="experience-item">
    <div class="experience-header">
        <h3>Your Job Title</h3>
        <span class="company">Company Name</span>
        <span class="period">2020 - Present</span>
    </div>
    <p>Job description and responsibilities...</p>
    <ul>
        <li>Achievement 1</li>
        <li>Achievement 2</li>
    </ul>
</div>
```

### Projects

Add your projects to the projects section:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Project Name</h3>
        <div class="project-links">
            <a href="github-link" class="project-link"><i class="fab fa-github"></i></a>
            <a href="live-link" class="project-link"><i class="fas fa-external-link-alt"></i></a>
        </div>
    </div>
    <p>Project description...</p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
</div>
```

### Blog Posts

Add your blog posts:

```html
<article class="blog-post">
    <div class="post-meta">
        <span class="post-date">Date</span>
        <span class="post-category">Category</span>
    </div>
    <h3>Blog Post Title</h3>
    <p>Blog post excerpt...</p>
    <a href="blog-post-link" class="read-more">Read More →</a>
</article>
```

### Profile Image

Replace the placeholder image:
1. Add your profile image to the project folder
2. Update the `src` attribute in the profile image element:
```html
<img src="path/to/your/image.jpg" alt="Your Name" id="profile-img">
```

## Styling Customization

### Colors
The website uses a clean color scheme inspired by GitHub. You can customize colors in `styles.css`:

- Primary Blue: `#0366d6`
- Text Dark: `#24292e`
- Text Medium: `#586069`
- Text Light: `#6a737d`
- Background: `#fafafa`
- Borders: `#e1e5e9`

### Fonts
The website uses Inter font family. You can change fonts by updating the `font-family` property in the body selector.

### Layout
- Sidebar width: 20% (customizable in `.sidebar` width property)
- Content area: 80% (automatically adjusts)
- Responsive breakpoints: 768px and 480px

## Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Your site will be deployed automatically
3. Customize the domain in Netlify settings

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy your site
3. Customize settings in the Vercel dashboard

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Included

- ✅ Responsive design
- ✅ Smooth navigation
- ✅ Hover effects and animations
- ✅ Scroll to top button
- ✅ Mobile-friendly layout
- ✅ Clean typography
- ✅ Professional color scheme
- ✅ Easy customization
- ✅ SEO-friendly structure

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to fork this project and customize it for your own portfolio. If you have suggestions for improvements, please open an issue or submit a pull request.

## Support

If you need help customizing your portfolio or have questions, please open an issue in the repository.
