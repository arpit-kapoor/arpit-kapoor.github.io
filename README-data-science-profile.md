# Data Science Profile - Single Page Website

This branch contains a modern, single-page data science profile website for Arpit Kapoor, built with Bootstrap 5 and modern animations.

## Features

### 🎨 Modern Design
- **Clean, professional layout** with smooth animations
- **Bootstrap 5** for responsive design
- **Custom CSS animations** and transitions
- **Gradient backgrounds** and modern color scheme
- **Mobile-first responsive design**

### 🚀 Animations & Interactions
- **AOS (Animate On Scroll)** library for scroll-triggered animations
- **Smooth scrolling** navigation
- **Parallax effects** on hero section
- **Hover animations** on cards and buttons
- **Animated skill progress bars**
- **Timeline animations** for experience section

### 📱 Responsive Design
- **Mobile-optimized** layout
- **Tablet-friendly** navigation
- **Desktop experience** with full animations
- **Cross-browser compatibility**

### 📊 Content Sections

1. **Hero Section**
   - Animated profile image
   - Gradient background with floating elements
   - Call-to-action buttons

2. **About Section**
   - Professional summary
   - Educational background
   - Research focus areas

3. **Experience Timeline**
   - Interactive timeline design
   - Professional positions at Bureau of Meteorology, Quince, 3Qi Labs, Bomotix
   - Alternating layout for visual appeal

4. **Technical Skills**
   - Animated progress bars
   - Categorized skill sets
   - Visual skill level indicators

5. **Featured Projects**
   - Project showcase with hover effects
   - Links to code repositories and papers
   - Image overlays with project details

6. **Publications**
   - Academic publications list
   - Journal articles and conference papers
   - Timeline-style layout

7. **Contact Section**
   - Contact information
   - Social media links
   - Professional networking profiles

## Technical Implementation

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS Grid and Flexbox
- **Bootstrap 5.3.0** - Responsive framework
- **Font Awesome 6.4.0** - Icons
- **AOS 2.3.4** - Scroll animations
- **Google Fonts (Inter)** - Typography
- **Vanilla JavaScript** - Interactions and animations

### Key Features
- **Smooth scroll navigation** with active state indicators
- **Intersection Observer API** for scroll-triggered animations
- **CSS Custom Properties** for consistent theming
- **Progressive enhancement** with fallbacks
- **Optimized performance** with external CDN resources

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Graceful degradation for older browsers

## Files

- `data-science-profile.html` - Main single-page website
- `index-ds.html` - Redirect page to the main profile
- `README-data-science-profile.md` - This documentation

## Usage

1. Open `data-science-profile.html` in a web browser
2. Or use `index-ds.html` for automatic redirection
3. Navigate using the fixed navigation bar
4. All sections are on a single page with smooth scrolling

## Customization

### Colors
The color scheme can be customized by modifying CSS custom properties in the `:root` selector:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Content
- Update personal information in the HTML
- Replace image paths with actual profile and project images
- Modify social media links and contact information
- Add or remove projects and publications as needed

### Animations
- Adjust AOS settings in the JavaScript initialization
- Modify CSS animation durations and effects
- Customize scroll-triggered behaviors

## Performance Optimizations

- **CDN resources** for faster loading
- **Optimized images** (ensure images are compressed)
- **Minimal JavaScript** footprint
- **Efficient CSS** with modern properties
- **Lazy loading** compatible structure

## Future Enhancements

Potential improvements could include:
- Dark mode toggle
- Multi-language support
- Blog integration
- Contact form with backend
- Advanced filtering for projects/publications
- Integration with GitHub API for dynamic project updates

---

**Created**: December 2024  
**Author**: AI Assistant  
**Framework**: Bootstrap 5 + Custom CSS/JS  
**Purpose**: Professional data science portfolio showcase
