# Isaac Carson Portfolio Website

A clean, modern portfolio website showcasing fabrication, mechanical design, CNC machining, and engineering projects.

## Design Overview

### Color Palette
The design uses a warm, earthy color scheme based on research of successful engineering portfolios:

- **Primary Background**: `#F5F1E8` (Warm Cream)
- **Secondary Background**: `#FFFFFF` (Clean White)
- **Accent Sage**: `#8B9A7E` (Muted Sage Green)
- **Dark Primary**: `#2C2C2C` (Charcoal)
- **Dark Secondary**: `#5A5550` (Warm Brown-Gray)
- **Accent Brown**: `#8C7A6B` (Earth Brown)
- **Light Sage**: `#B8C4AE` (Soft Sage)
- **Border**: `#D8D3C8` (Subtle Beige)

### Features

1. **Fixed Navigation** with resume download link
2. **Hero Section** with space for CAD motion rendering
3. **Featured Projects** section with clickable project cards
4. **Fabrication Gallery** for smaller projects
5. **Photography Section** (subtle, non-distracting)
6. **Contact Form** for inquiries
7. **Responsive Design** for all screen sizes

## File Structure

```
isaaccarson/
├── index.html              # Main homepage
├── about.html              # About page
├── style.css               # Main stylesheet
├── project.css             # Project page styles
├── script.js               # JavaScript functionality
├── resume.pdf              # Your resume (ADD THIS)
├── projects/
│   ├── dentist-sign.html   # Project detail page
│   ├── guitar.html         # (Create for guitar project)
│   └── mandrel.html        # (Create for mandrel project)
├── images/
│   ├── dentist-sign/       # Project images
│   ├── gallery/            # CREATE: Gallery images
│   ├── photography/        # CREATE: Photography images
│   └── project-*.jpg       # Featured project covers
└── videos/
    └── hero-video.mp4      # CAD rendering (ADD THIS)
```

## Setup Instructions

### 1. Add Your Images

Create the following folders and add images:

```bash
mkdir -p images/gallery
mkdir -p images/photography
```

- Add 6+ images to `images/gallery/` (named item1.jpg, item2.jpg, etc.)
- Add 4+ images to `images/photography/` (named photo1.jpg, photo2.jpg, etc.)
- Replace placeholder images in `images/` folder

### 2. Add CAD Motion Rendering

- Export your CAD motion rendering as MP4
- Save as `videos/hero-video.mp4`
- Replace the placeholder div in the hero section

### 3. Add Your Resume

- Save your resume as `resume.pdf` in the root folder
- Update the links in navigation to point to your actual resume

### 4. Update Contact Information

In **index.html** (line ~161):
```html
<form class="contact-form" action="https://formspree.io/f/YOUR-FORM-ID" method="POST">
```

Replace `YOUR-FORM-ID` with your Formspree ID, or:
- Use a different form service
- Build your own backend
- Use a simple mailto link

In **index.html** (line ~185) and footer links:
```html
<a href="mailto:isaac@example.com">isaac@example.com</a>
```

Replace with your actual email address.

### 5. Update Social Links

In the footer of all HTML files, update:
```html
<a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
<a href="https://github.com/yourprofile" target="_blank">GitHub</a>
```

Replace with your actual social media profiles.

### 6. Create Additional Project Pages

Use `projects/dentist-sign.html` as a template:

1. Copy the file: `cp projects/dentist-sign.html projects/guitar.html`
2. Update the content with your project information
3. Replace images with your project images
4. Update the title and meta tags

### 7. Customize Content

Update the following in **index.html**:

- **Hero title** (line ~43): Update your tagline
- **Hero description** (line ~48): Update your intro text
- **Project cards** (lines ~86-125): Update titles, descriptions, and links
- **Footer** (line ~190): Update copyright year and name

## Design Principles Applied

✅ **Clean and Concise**: Tight spacing between sections, no excess whitespace  
✅ **Not Clunky or Boxy**: Smooth layouts with grid systems  
✅ **Balanced Corners**: 4-6px border radius (not overly rounded, not sharp)  
✅ **Warm Color Palette**: Creams, beiges, sages, grays, and browns  
✅ **Professional Yet Approachable**: Works for clients, employers, and family  
✅ **Photography Integration**: Subtle section that doesn't distract from main work  
✅ **Resume Access**: Clear navigation link and download option  
✅ **Contact Accessibility**: Form and direct email option  

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Responsive Breakpoints

- **Desktop**: 1024px+
- **Tablet**: 768px - 1023px
- **Mobile**: 320px - 767px

## Performance Optimization

- Lazy loading for images (via JavaScript)
- Optimized CSS with minimal redundancy
- Smooth scroll behavior
- Intersection Observer for scroll animations
- Minimal JavaScript dependencies

## Next Steps

1. Add all images to appropriate folders
2. Create CAD motion rendering video
3. Add your resume PDF
4. Update all contact information
5. Create additional project pages
6. Test on multiple devices
7. Deploy to hosting service

## Deployment

You can deploy this site to:
- **GitHub Pages** (free, easy)
- **Netlify** (free, custom domain support)
- **Vercel** (free, automatic deployments)
- **Traditional web hosting** (upload via FTP)

## Questions or Issues?

If you need to:
- Add more sections
- Modify the color scheme
- Adjust spacing or layout
- Add new features

Just let me know and I can help update the code!

---

**© 2026 Isaac Carson. All rights reserved.**
