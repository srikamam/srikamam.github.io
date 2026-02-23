# Personal Portfolio Website

A modern, responsive personal portfolio website with a left sidebar profile and main content area. Optimized for GitHub Pages hosting.

## Features

✨ **Clean Modern Design** - Professional and elegant layout with cream and blue color scheme
📱 **Fully Responsive** - Works on desktop, tablet, and mobile devices
🎨 **Customizable** - Easy to modify colors, fonts, and content
🔗 **Smooth Navigation** - Smooth scrolling between sections
📊 **Multiple Sections** - About, Education, Work Experience, and Academic Projects
🚀 **GitHub Pages Ready** - Easy deployment on GitHub.io

## File Structure

```
personal_website/
├── index.html      # Home page (About & Education)
├── work.html       # Work Experience page
├── projects.html   # Academic Projects page
├── styles.css      # Styling (shared across all pages)
├── script.js       # JavaScript functionality
├── profile.jpg     # Profile image (add your image here)
├── README.md       # This file
└── DEPLOY.md       # Deployment guide
```

## Customization Guide

### 1. **Update Profile Information**
   - The sidebar appears on all pages (About/Education, Work Experience, and Academic Projects)
   - Replace placeholder text with your actual information in any HTML file
   - Update education details in `index.html`
   - Add your work experience in `work.html`
   - Include your academic projects in `projects.html`

### 2. **Add Your Profile Image**
   - Save your profile photo as `profile.jpg` in the root directory
   - Or update the `src` in `index.html` if using a different filename:
     ```html
     <img src="your-image-name.jpg" alt="Your Name" class="profile-image">
     ```

### 3. **Customize Colors**
   Edit the CSS variables in `styles.css` (line 7-12):
   ```css
   :root {
       --primary-color: #6366f1;      /* Change primary blue */
       --primary-dark: #4f46e5;       /* Change dark blue */
       /* ... other colors ... */
   }
   ```

### 4. **Update Social Media Links**
   Update the social links in `index.html`:
   ```html
   <a href="https://linkedin.com/in/yourprofile" class="social-icon">in</a>
   ```

### 5. **Add CV Download**
   - Save your CV as a PDF file (e.g., `cv.pdf`)
   - Update the button in the sidebar:
     ```html
     <a href="cv.pdf" download="YourName_CV.pdf" class="cv-button">Download CV</a>
     ```

## 🚀 GitHub Pages Deployment

### Quick Setup (Recommended)

1. **Create a GitHub Repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it: `username.github.io` (replace `username` with your GitHub username)
   - Make it **Public**
   - Click "Create repository"

2. **Upload Your Files**
   - Clone the repository: `git clone https://github.com/username/username.github.io.git`
   - Copy all files from this project into the cloned folder
   - Push to GitHub:
     ```bash
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```

3. **Access Your Website**
   - Your site will be live at: `https://username.github.io`
   - It may take 1-2 minutes to deploy

### Alternative: Deploy to a Project Repository

If you want to use a different repository name:

1. Create a repo named `my-portfolio` (or any name)
2. Upload your files
3. Go to **Settings** → **Pages** → Set source to `main` branch
4. Your site will be at: `https://username.github.io/my-portfolio/`
5. Update internal links to include the base path if needed

📚 **For detailed step-by-step instructions**, see [DEPLOY.md](DEPLOY.md)

1. Open `index.html` in a web browser
2. The website includes:
   - **Navigation Bar**: Top menu with About, Education, Work Experience, and Academic Projects
   - **Left Sidebar**: Profile info, photo, social links, and CV download
   - **Main Content**: About section, education, experience, and projects

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Tips

- Keep content concise and professional
- Use high-quality profile images
- Update section content regularly
- Test on mobile devices before publishing
- Ensure all links are working correctly

## Future Enhancements

- Add contact form
- Include portfolio/case studies section
- Add dark mode toggle
- Include skills visualization (charts/graphs)
- Add blog section

---

**Ready to deploy?** Upload all files to your web hosting service and share the link!
