# Khushboo Verma - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Smooth Animations**: Engaging scroll animations and transitions
- **Interactive Elements**: Draggable skill cards, project hover effects
- **Modern UI**: Clean and professional design with gradient accents
- **Contact Form**: Functional contact form for visitor inquiries
- **Fast Loading**: Optimized for performance

## 🚀 Sections

1. **Hero Section**: Introduction with name and title
2. **About Me**: Professional background and expertise
3. **Skills**: Interactive skill cards showcasing technical abilities
4. **Projects**: Portfolio of completed projects with links
5. **Contact**: Contact information and form

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables, Flexbox, Grid)
- JavaScript (ES6+)
- Font Awesome Icons

## 📦 How to Deploy on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **+** icon in the top right corner and select **New repository**
3. Name your repository: `<your-username>.github.io` (e.g., `khushboo-verma.github.io`)
   - **Important**: For a user site, the repository must be named exactly `<username>.github.io`
   - Alternatively, you can name it anything (e.g., `portfolio`) and it will be available at `<username>.github.io/portfolio`
4. Set the repository to **Public**
5. Click **Create repository**

### Step 2: Initialize Git and Push Code

Open your terminal/command prompt in the portfolio folder and run:

```bash
# Initialize Git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit - Portfolio website"

# Add remote repository (replace <your-username> with your GitHub username)
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in the left sidebar under "Code and automation")
4. Under **Source**, select **Deploy from a branch**
5. Under **Branch**, select **main** and **/ (root)**, then click **Save**
6. Wait a few minutes for deployment to complete

### Step 4: Access Your Website

Your portfolio will be live at:
- For user site: `https://<your-username>.github.io/`
- For project site: `https://<your-username>.github.io/<repository-name>/`

## 🎨 Customization

### Update Personal Information

1. **index.html**: Update name, title, about text, contact info, and social links
2. **Project Links**: Replace placeholder project links with your actual GitHub repos and live demos
3. **Profile Picture**: Replace the emoji in the CSS or add an actual image
4. **Colors**: Modify CSS variables in `style.css` under `:root` section

### Add Your Own Projects

In `index.html`, find the Projects section and modify each project card:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-image-url" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="your-live-link" target="_blank" class="project-link">
                    <i class="fas fa-external-link-alt"></i> Live
                </a>
                <a href="your-github-link" target="_blank" class="project-link">
                    <i class="fab fa-github"></i> Code
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Tech1</span>
            <span class="tech-tag">Tech2</span>
        </div>
    </div>
</div>
```

### Update Contact Information

Replace these in `index.html`:
- Phone number
- Email address
- LinkedIn URL
- GitHub URL

## 📱 Mobile Responsive

The portfolio is fully responsive and includes:
- Mobile navigation menu
- Adaptive layouts for tablets and phones
- Touch-friendly interactive elements
- Optimized images and performance

## 🔄 Future Updates

To update your portfolio after initial deployment:

```bash
# Make your changes to the files

# Add changes
git add .

# Commit changes
git commit -m "Description of changes"

# Push to GitHub
git push
```

Changes will be reflected on your live site within a few minutes.

## 📄 License

This portfolio template is free to use for personal projects.

## 🤝 Connect

- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/khushboo-verma)
- **GitHub**: [Your GitHub Profile](https://github.com/khushboo-verma)
- **Email**: khushboo.verma@email.com

---

**Made with ❤️ by Khushboo Verma**
