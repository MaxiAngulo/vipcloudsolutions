<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

# VIPCloud Solutions Website - Development Guidelines

This workspace contains a static website for VIPCloud Solutions. The website is built using HTML, CSS, and JavaScript only, without any server-side processing or frameworks.

## Project Structure

- `index.html` - Main HTML file
- `css/styles.css` - Main stylesheet
- `js/main.js` - JavaScript functionality
- `assets/` - Directory for images and other static assets

## Coding Guidelines

### HTML
- Use semantic HTML5 elements
- Ensure all images have proper alt text
- Maintain proper heading hierarchy (h1, h2, etc.)
- Keep accessibility in mind (ARIA attributes where needed)
- Validate HTML against W3C standards

### CSS
- Follow BEM (Block Element Modifier) naming convention when possible
- Use CSS variables for consistent theming
- Organize CSS by components/sections
- Mobile-first approach with responsive design
- Minimize use of !important

### JavaScript
- Use modern ES6+ syntax where appropriate
- Prefer const and let over var
- Comment complex logic
- Handle errors gracefully in form submissions
- Prioritize vanilla JavaScript over libraries when possible

### Performance
- Optimize image sizes before adding to the project
- Minimize unnecessary DOM manipulation
- Combine related functions where it makes sense
- Consider lazy loading for images below the fold

### General
- Maintain consistent code indentation (2 spaces)
- Keep functions small and focused on a single task
- Add descriptive comments for complex sections
- Follow a consistent naming convention across all files

## Deployment Notes

This website is designed to be deployed on any static hosting service. All links are relative, and no server-side processing is required.

## Feature Requests

When suggesting new features or improvements:
- Focus on static-only solutions that don't require server-side processing
- Prioritize performance and user experience
- Maintain the existing visual style and branding
- Consider mobile responsiveness for all new additions
