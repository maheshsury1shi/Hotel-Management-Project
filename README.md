# Royal Palace Hotel Website

A responsive, professional hotel website built with Bootstrap 5 and modern web technologies.

## 🏨 Project Overview

Royal Palace is a beautifully designed hotel website featuring:
- Responsive design that works on all devices
- Hotel information and services showcase
- Photo gallery with lightbox effects
- Events management section
- Pricing tables
- Team member profiles
- Contact form for inquiries
- Smooth scrolling navigation

## 📁 Project Structure

```
Royal Palace Orignal/
├── index.html                 # Main homepage
├── inner-page.html            # Inner page template
├── portfolio-details.html     # Gallery item details
├── README.md                  # Project documentation
├── Readme.txt                 # Original template info
├── forms/
│   ├── contact.php            # Contact form handler
│   └── Readme.txt
├── assets/
│   ├── css/
│   │   └── style.css          # Custom styling
│   ├── js/
│   │   └── main.js            # Custom JavaScript
│   ├── img/                   # Images (portfolio, team, testimonials)
│   ├── scss/                  # SCSS source (pro version)
│   └── vendor/                # Third-party libraries
│       ├── bootstrap/         # Bootstrap 5
│       ├── bootstrap-icons/   # Icon library
│       ├── boxicons/          # Icon animations
│       ├── glightbox/         # Lightbox gallery
│       ├── isotope-layout/    # Portfolio filtering
│       ├── remixicon/         # Icon fonts
│       └── swiper/            # Touch carousel
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with Bootstrap 5
- **JavaScript** - Interactive features
- **Bootstrap 5** - Responsive framework
- **PHP** - Backend form handling
- **Third-party Libraries:**
  - Glightbox - Image lightbox
  - Swiper - Touch carousel slider
  - Isotope - Portfolio grid filtering
  - Bootstrap Icons, Boxicons, Remix Icons

## 🎨 Color Scheme

- **Primary Color:** #85b0be (Teal/Blue)
- **Secondary Colors:** Various shades for contrast and accessibility

## 📋 Key Features

### Navigation
- Fixed transparent header with logo
- Smooth scroll navigation
- Mobile-responsive hamburger menu
- Active state tracking on scroll

### Sections
- **Hero** - Eye-catching landing banner
- **About** - Hotel information and highlights
- **Services** - Amenities and services
- **Gallery** - Photo gallery with lightbox
- **Events** - Event management section
- **Pricing** - Room/package pricing
- **Team** - Staff profiles
- **Contact** - Contact form and information

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimization
- Touch-friendly interface

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Optional: PHP server for contact form functionality

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/royal-palace.git
cd royal-palace
```

2. Open in browser
```bash
# Simple way - just open index.html in your browser
# Or use a local server for better experience
```

3. For local PHP development
```bash
# Using PHP built-in server
php -S localhost:8000

# Then visit http://localhost:8000
```

## 💬 Contact Form

The contact form is handled by `forms/contact.php`. To enable:

1. Ensure your hosting supports PHP
2. Update sender email in `contact.php`
3. Customize validation in `forms/validate.js`

## 📝 Customization

### Update Hotel Information
- Edit content in `index.html`
- Update images in `assets/img/`
- Replace logo with your hotel's logo

### Styling
- Custom CSS in `assets/css/style.css`
- Modify colors and fonts as needed
- SCSS files available in pro version only

### Navigation Links
- Update navigation items in header
- Modify section IDs for smooth scrolling
- Update mobile menu in `assets/js/main.js`

## 🐛 Known Issues & Notes

- Path references use mixed slashes (backslash in some places)
- SCSS source files only available in pro version
- Some pages still contain template placeholder text
- inner-page.html still references "Vlava" template name

## 📄 License

This project uses the free Vlava Bootstrap template from BootstrapMade.com
- Template License: https://bootstrapmade.com/license/
- Template URL: https://bootstrapmade.com/vlava-free-bootstrap-one-page-template/

## 👥 Credits

**Created by:** Mahesh Suryawanshi & Team

**Based on:** Vlava Template by BootstrapMade

## 🤝 Contributing

Feel free to fork this project and submit pull requests with improvements.

## ❓ Support

For issues or questions, please create an issue in the repository.

---

**Last Updated:** June 18, 2026
