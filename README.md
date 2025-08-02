# Campus Lost & Found Portal

A modern, responsive web application for managing lost and found items on campus.

## 🚀 Quick Start

### Option 1: Open Directly in Browser
1. Simply double-click on `index.html` to open the application in your default web browser
2. Navigate through all pages using the navigation menu

### Option 2: Using Local Server (Recommended)
1. Open your terminal/command prompt
2. Navigate to this project folder
3. Run one of these commands:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
npx serve .
```

**Using PHP:**
```bash
php -S localhost:8000
```

4. Open your browser and go to `http://localhost:8000`

## 📁 Project Structure

```
lost and found portal/
├── index.html          # Home page
├── lost.html          # Report lost item form
├── found.html         # Report found item form
├── browse.html        # Browse all items
├── login.html         # Login/Register page
├── style.css          # Main stylesheet
└── README.md          # This file
```

## 🎯 Features

- **Home Page**: Welcome banner and platform description
- **Report Lost Item**: Form to submit lost item reports
- **Report Found Item**: Form to submit found item reports
- **Browse Items**: Grid view of all items with modal details
- **Login/Register**: Toggle between login and registration forms
- **Responsive Design**: Works on mobile, tablet, and desktop
- **Modern UI**: Clean, campus-themed design with smooth animations

## 🎨 Design Features

- Campus color scheme (navy blue, teal accents)
- Card-based layout for items
- Smooth hover animations
- Modal popups for item details
- Fully responsive design
- Accessible form fields

## 🧪 Testing the Application

1. **Home Page**: Click through all navigation links
2. **Forms**: Try submitting the lost and found item forms
3. **Browse Page**: Click "View Details" on items to see modals
4. **Login Page**: Toggle between login and register modes
5. **Responsive**: Resize your browser window to test mobile layout

## 🔧 Customization

- **Colors**: Edit the CSS variables in `style.css` (lines 1-10)
- **Content**: Modify the dummy data in `browse.html` (lines 45-75)
- **Images**: Replace the base64 SVG placeholders with real images
- **Forms**: Add backend integration for form submission

## 📱 Browser Compatibility

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers

## 🚀 Deployment Options

### GitHub Pages
1. Push this code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch and deploy

### Netlify
1. Drag and drop this folder to netlify.com
2. Instant deployment

### Vercel
1. Install Vercel CLI
2. Run `vercel` in this directory

## 📞 Support

This is a static frontend demo. For production use, you'll need to:
- Add a backend server
- Implement database storage
- Add user authentication
- Set up image upload functionality

---

**Made with ❤️ for campus communities** 