# Mintlify Documentation Website - HTML & CSS Recreation

A desktop-first documentation-style website inspired by Mintlify, built purely with HTML and CSS for the Web Dev Cohort 2026 assignment.

## 📋 Project Overview

This project recreates the core structure and design of Mintlify's documentation website, focusing on clean layout, readability, and visual fidelity. Built entirely with semantic HTML and custom CSS (no frameworks or JavaScript).

## ✅ Sections Recreated

### 1. Top Navigation Bar
- Clean fixed navigation with backdrop blur effect
- Logo with custom SVG icon
- Navigation links (Docs, Components, Showcase, Pricing, Blog)
- Login and "Start for free" CTA button
- Sticky positioning for persistent access

### 2. Hero Section
- Large, bold headline with gradient text effect
- Descriptive subheading
- Email input field with CTA button
- Large background illustration with mock documentation preview
- Two-column grid layout

### 3. Documentation Preview Section
- Functional-looking sidebar navigation with three sections:
  - Getting Started
  - Guides
  - Advanced
- Main content area with card-based layout
- Four feature cards with icons and descriptions
- Hover effects on interactive elements

### 4. Trusted By / Company Logos
- Section displaying "Trusted by the best teams"
- 6-column grid layout with placeholder logos
- Companies: Stripe, Vercel, Replicate, Anthropic, Clerk, Resend

### 5. Feature Highlights
- Two alternating two-column sections
- **Section 1**: "Write in Markdown" - Code editor mockup with syntax highlighting
- **Section 2**: "Collaborate with your team" - Visual representation of team collaboration
- Feature lists with checkmarks
- Reverse layout for visual variety

### 6. Intelligent Assistant / UI Preview
- Large centered mockup of AI chat interface
- Chat bubble design with user and assistant messages
- Typing indicator animation-ready structure
- Window chrome with dots and title bar

### 7. Enterprise Features Section
- Grid layout of 6 feature cards (3 columns × 2 rows)
- Features include:
  - SOC 2 Compliance
  - SAML SSO
  - Advanced Analytics
  - Custom Integrations
  - 99.9% Uptime SLA
  - Priority Support
- Icon-driven design with hover effects

### 8. Case Studies / Customer Stories
- Three customer testimonial cards
- Each card includes:
  - Colored header image (gradient backgrounds)
  - Company name
  - Testimonial quote
  - Author avatar and information
- Companies featured: Stripe, Vercel, Replicate

### 9. Final Call-To-Action
- Bold gradient background (green to mint)
- Large heading: "Ready to build beautiful docs?"
- Two prominent CTA buttons (solid and outlined)
- Trust indicators: "No credit card required • Free 14-day trial"

### 10. Footer
- Comprehensive 5-column layout:
  - Company info with logo and description
  - Product links
  - Resources links
  - Company links
  - Legal links
- Bottom section with copyright and social media links
- Dark theme (Woodsmoke #08090B background)

## 🎨 Design Specifications

### Fonts
- **Primary Font**: Inter (Google Fonts)
- **Fallback Stack**: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif
- **Code Font**: Monaco, Menlo, Courier New, monospace

### Color Palette
```css
--primary-green: #18E299     /* Mountain Meadow - Main brand color */
--primary-mint: #90ECC5      /* Riptide - Secondary accent */
--primary-teal: #10B981      /* Success/positive */
--primary-orange: #F59E0B    /* Warning/highlight */
--text-dark: #08090B         /* Woodsmoke - Primary text */
--text-gray: #6B7280         /* Secondary text */
--text-light: #9CA3AF        /* Tertiary text */
--bg-light: #F9FAFB          /* Light background */
--bg-lighter: #F3F4F6        /* Lighter background */
--border-color: #E5E7EB      /* Borders */
```

### Typography Scale
- Hero Title: 64px / 800 weight
- Section Headings: 48px / 800 weight
- Subheadings: 20-24px / 700 weight
- Body Text: 15-18px / 400-500 weight
- Small Text: 13-14px / 500-600 weight

### Spacing
- Section padding: 80-120px vertical
- Container max-width: 1400px
- Grid gaps: 24-80px (context-dependent)
- Card padding: 32-40px

### Border Radius
- Small elements (buttons): 8-10px
- Cards: 12px
- Large containers: 16px

### Shadows
- Light hover: `0 8px 24px rgba(24, 226, 153, 0.12)`
- Medium elevation: `0 12px 32px rgba(0, 0, 0, 0.1)`
- Heavy elevation: `0 20px 60px rgba(0, 0, 0, 0.15)`

## 🛠️ Technical Implementation

### HTML Structure
- Semantic HTML5 elements (`<nav>`, `<section>`, `<footer>`)
- Organized with clear section comments
- Proper heading hierarchy (h1 → h2 → h3)
- Accessible markup with meaningful class names

### CSS Techniques
- **CSS Grid**: Multi-column layouts throughout
- **Flexbox**: Navigation, cards, and alignment
- **Custom Properties**: CSS variables for consistent theming
- **Gradient Effects**: Text gradients and background gradients
- **Pseudo-elements**: Decorative elements and effects
- **Hover States**: Interactive feedback on all clickable elements
- **Box Shadows**: Depth and elevation
- **Backdrop Filter**: Glassmorphism effect on navigation

### No External Dependencies
- ✅ No JavaScript
- ✅ No CSS frameworks (no Tailwind, Bootstrap, etc.)
- ✅ No animation libraries
- ✅ Only external resource: Google Fonts (Inter)

## 📁 File Structure
```
.
├── index.html          # Main HTML structure
├── styles.css          # All custom styles
├── README.md           # This file
└── images/            # (Optional) Folder for custom images/icons
```

## 🖼️ Assets & Images

### Current Implementation
- Official Mintlify logo SVG (full logo with text and icon versions)
- Gradient backgrounds matching brand colors
- Mock documentation preview built with CSS
- Icon-only version for smaller contexts

### Brand Assets Source
All Mintlify brand assets sourced from: [BrandFetch - Mintlify](https://brandfetch.com/mintlify.com)

### Recommendations for Enhancement
- Add actual company logos from [BrandFetch](https://brandfetch.com/mintlify.com)
- Include hero illustration image
- Add icons for feature cards
- Include screenshots or mockups for feature sections

## 🚀 How to View

### Local Viewing
1. Clone this repository
2. Open `index.html` in your browser (Chrome, Firefox, Edge, Safari)
3. No build process or server required!

### GitHub Pages Hosting (Optional)
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select main branch as source
4. Your site will be live at: `https://[username].github.io/[repo-name]/`

## 🎯 Design Fidelity

### Layout Accuracy
- ✅ All 10 required sections implemented
- ✅ Grid-based layouts matching original structure
- ✅ Sidebar navigation with hierarchical menu
- ✅ Card-based content presentation
- ✅ Multi-column footer

### Visual Consistency
- ✅ Green-mint color scheme with modern aesthetic
- ✅ Inter font family throughout
- ✅ Consistent spacing and padding
- ✅ Professional hover effects and transitions
- ✅ Proper visual hierarchy with typography

### Content Organization
- ✅ Clear section separation
- ✅ Logical content flow from top to bottom
- ✅ Balance between text and visual elements
- ✅ Readable typography with proper line-height
- ✅ Adequate white space and breathing room

## 📊 Browser Compatibility
- Chrome/Edge (Chromium): ✅ Fully supported
- Firefox: ✅ Fully supported
- Safari: ✅ Fully supported
- Internet Explorer: ❌ Not supported (uses modern CSS)

## ✅ Assignment Compliance

### Brand Assets Integrated
- ✅ Official Mintlify logo SVG in navbar
- ✅ Official Mintlify logo SVG in footer (white version)
- ✅ Brand color palette: Mountain Meadow (#18E299), Riptide (#90ECC5), Woodsmoke (#08090B)
- ✅ Hero section gradient matching brand aesthetics
- ✅ Icon and full logo versions available

### Requirements Met
- ✅ Desktop-first design (no mobile responsiveness)
- ✅ Only HTML and CSS used
- ✅ No JavaScript
- ✅ No Tailwind CSS or other frameworks
- ✅ No animations or complex effects
- ✅ All 10 sections implemented
- ✅ Fonts and colors match Mintlify closely
- ✅ Public GitHub repository
- ✅ Comprehensive README with explanations

### Constraints Followed
- ✅ Semantic HTML structure
- ✅ Custom CSS only
- ✅ Desktop viewport (1440px+ optimal)
- ✅ Static content (no dynamic elements)
- ✅ Clean, maintainable code

## 📝 Notes

### Challenges & Solutions
1. **Gradient Text**: Used `-webkit-background-clip` with fallback
2. **Backdrop Blur**: Implemented on navigation for modern effect
3. **Grid Layouts**: Extensive use of CSS Grid for precise control
4. **Visual Hierarchy**: Careful attention to font weights and sizes

### Future Enhancements (Beyond Assignment Scope)
- Add actual images and brand assets
- Implement responsive design for mobile/tablet
- Add JavaScript for interactive elements
- Include smooth scroll animations
- Integrate real search functionality

## 👨‍💻 Author
Created for Web Dev Cohort 2026 - HTML & CSS Assignment

**Submission Date**: February 7, 2026

---

## 📸 Screenshots

*(Add screenshots of your final output here)*

1. Hero Section
2. Documentation Preview
3. Features Section
4. Enterprise Section
5. Full Page Overview

---

**License**: Educational project - for assignment purposes only
