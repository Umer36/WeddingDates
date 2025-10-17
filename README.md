# Wedding Celebrations 2025 🎉

A beautiful, modern wedding schedule webpage showcasing the wedding celebrations of three friends: Aman Sayyad, Aman Vijapure, and Sahil Pakhali.

## 🌐 Live Demo

**[View Live Website](https://wedding-dates.vercel.app/)**

- **Vercel**: https://wedding-dates.vercel.app/
- **GitHub**: https://github.com/Umer36/WeddingDates

## Features

- 🎨 Modern, elegant design with gradient backgrounds
- 📱 Fully responsive for all devices
- ✨ Smooth animations and hover effects
- 💝 Floating heart animations
- 🎯 Color-coded events for each couple
- 📅 Timeline-style event display
- 🌟 Glass-morphism design elements

## Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface

1. **Create a new repository on GitHub**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it something like `wedding-schedule` or `wedding-celebrations-2025`
   - Make it public

2. **Upload files**
   - Upload `index.html` to the repository
   - Upload `README.md` to the repository

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your site**
   - Your site will be available at: `https://yourusername.github.io/repository-name`

### Method 2: Using Git Commands

```bash
# Initialize git repository
git init

# Add files
git add .

# Commit files
git commit -m "Initial commit: Wedding schedule webpage"

# Add remote repository (replace with your repo URL)
git remote add origin https://github.com/yourusername/wedding-schedule.git

# Push to GitHub
git branch -M main
git push -u origin main

# Enable GitHub Pages in repository settings
```

## Customization

### Adding More Events
To add more events, copy an existing event card structure in `index.html` and modify:
- Date and day
- Event name and type
- Color scheme (create new CSS classes)

### Changing Colors
Modify the CSS color variables for each couple:
- `.aman-sayyad` - Red theme (#e74c3c)
- `.aman-vijapure` - Green theme (#27ae60)
- `.sahil-pakhali` - Blue theme (#3498db)

### Adding New Couples
1. Create new CSS classes with unique colors
2. Add new event cards following the existing structure
3. Update the legend section

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (Intersection Observer API)
- Google Fonts (Dancing Script, Poppins)
- Font Awesome Icons

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

This project is open source and available under the [MIT License](LICENSE).