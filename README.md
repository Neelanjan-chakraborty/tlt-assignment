# Create Your Profile Page - TLT Assignment

This is a responsive frontend implementation of the "Create Your Profile" page based on the provided Figma design.

## Features

- **Responsive Design**: Optimized for both desktop and mobile views
- **Modern UI**: Clean, professional interface with gradient backgrounds and glassmorphism effects
- **Semantic HTML5**: Well-structured, accessible markup
- **CSS Grid & Flexbox**: Modern layout techniques for responsive design
- **Form Components**: All required form elements including dropdowns and checkboxes
- **Interactive Elements**: Hover effects and focus states for better user experience

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet with responsive design
└── README.md          # This file
```

## Components Included

### Header Section
- TLT Logo with gradient background
- "Create Your Profile" page title
- User information display (avatar, name, role)

### Form Layout
- **Personal Information**: First Name, Last Name
- **Contact Details**: Email, Mobile Number
- **Professional Info**: Role dropdown, Specialty Type dropdown
- **Producer Checkbox**: "Is this user a producer?" with custom styling
- **Location**: Country and State/Province dropdowns
- **Action Buttons**: Cancel and Submit buttons

## Responsive Breakpoints

- **Desktop**: > 768px (default layout)
- **Mobile**: ≤ 768px (stacked layout, full-width buttons)
- **Small Mobile**: ≤ 480px (optimized for smaller screens)

## Design Features

### Color Scheme
- Dark gradient background (#1a1a2e → #16213e → #0f3460)
- White text with proper contrast ratios
- Gradient accents for branding elements (#667eea → #764ba2)
- Semi-transparent form containers with backdrop blur

### Typography
- Primary font: Inter (Google Fonts)
- Font weights: 400, 500, 600, 700
- Responsive font sizing

### Interactive Elements
- Smooth hover animations
- Focus states for accessibility
- Custom checkbox styling
- Button hover effects with elevation

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- CSS Grid and Flexbox support required

## How to View

1. Open `index.html` in any modern web browser
2. Or use a local development server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using VS Code Live Server extension
   Right-click index.html → "Open with Live Server"
   ```

## Mobile Testing

To test mobile responsiveness:

1. **Browser DevTools**: 
   - Press F12 → Click device toggle icon
   - Select different device presets
   
2. **Real Device Testing**:
   - Access via local network IP
   - Use browser's "Request Desktop Site" to compare

## Code Quality

- **Semantic HTML5**: Proper use of header, main, form elements
- **Accessible**: ARIA labels, proper form associations, keyboard navigation
- **Clean CSS**: BEM-like naming conventions, organized structure
- **Performance**: Optimized for fast loading, minimal dependencies

## Future Enhancements

- JavaScript form validation
- API integration for dynamic dropdowns
- Form submission handling
- Loading states and animations
- Dark/light theme toggle

## Assignment Compliance

✅ Responsive design (Desktop + Mobile)  
✅ All required form components  
✅ Visual hierarchy maintained  
✅ Color scheme consistency  
✅ Semantic HTML5 structure  
✅ Separate CSS file  
✅ Flexbox/Grid layout  
✅ No horizontal scroll on mobile  
✅ Static implementation (no JavaScript required)  

---

*Created for TLT Full Stack Developer Assignment*
