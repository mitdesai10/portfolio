# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Inspired by contemporary web design with a dark navy theme and teal accents.

## 🚀 Live Demo

Once deployed, your site will be available at: `https://yourusername.github.io/portfolio`

## ✨ Features

- Responsive design that works on all devices
- Smooth scrolling navigation
- Modern dark theme with professional color palette
- Animated sections on scroll
- Project showcase cards
- About section with skills
- Contact section
- Social media links

## 📦 Quick Start

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `portfolio` or `yourusername.github.io`)
4. Make it **Public**
5. Click "Create repository"

### 2. Upload Your Files

**Option A: Using GitHub Website**
1. On your new repository page, click "uploading an existing file"
2. Drag and drop `index.html` and `README.md`
3. Click "Commit changes"

**Option B: Using Git Command Line**
```bash
# Navigate to your project folder
cd path/to/your/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3. Deploy with GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down and click on **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait 1-2 minutes, then visit: `https://yourusername.github.io/portfolio`

## 🎨 Customization

### Personal Information
Edit `index.html` and update:
- Your name (line ~130)
- Your bio and description (lines ~134-136)
- Your email address (lines ~412, 426)
- Social media links (lines ~418-420)

### Profile Photo
Replace the placeholder image URL (line ~172):
```html
<img src="YOUR_IMAGE_URL" alt="Profile">
```

### Skills
Update the skills list (lines ~168-169) with your technologies.

### Projects
Modify the project cards (starting line ~184) with:
- Project titles
- Descriptions
- Technologies used
- Links to GitHub repos and live demos

### Colors
All colors are defined as CSS variables at the top of the `<style>` section. Customize them:
```css
:root {
    --navy: #0a192f;
    --green: #64ffda;
    /* ... more colors */
}
```

## 📱 Responsive Design

The website is fully responsive and works great on:
- Desktop computers
- Tablets
- Mobile phones

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- GitHub Pages (for hosting)

## 📝 License

Feel free to use this template for your personal portfolio. Please give credit by linking back to your inspiration!

## 🤝 Contributing

If you have suggestions for improvements:
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## 📧 Contact

- Email: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)

---

Made with ❤️ by [Your Name]
