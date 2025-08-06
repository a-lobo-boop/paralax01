# Website Structure Analysis - CorePulse Fitness Studio

## 🏗️ Website Sections Identified

### 1. **Navigation (Header)**
- Fixed navbar with blur effect
- Logo: "CorePulse" (Playfair Display font)
- Navigation links: Home, Features, Über uns, Services, Bewertungen, Kontakt
- Mobile hamburger menu

### 2. **Hero Section** 
- Full viewport height (100vh)
- Main headline: "Entfessle dein wahres Potenzial"
- Subtitle about CorePulse fitness partnership
- Two CTA buttons: "Jetzt starten" and "Mehr erfahren"
- Scroll indicator with chevron down icon
- Background: Gradient overlay with SVG pattern

### 3. **Features Section**
- Section title: "Warum CorePulse?"
- 6 feature cards in grid layout:
  1. Modernste Ausstattung (Dumbbell icon)
  2. Persönliche Betreuung (User-friends icon)
  3. Flexible Zeiten (Clock icon)
  4. Ganzheitlicher Ansatz (Heart icon)
  5. Community (Users icon)
  6. Mobile App (Mobile icon)

### 4. **Parallax Section**
- Mid-section call-to-action
- "Bereit für die Transformation?" headline
- "Schließe dich über 5.000 zufriedenen Mitgliedern an"
- "Kostenlose Probestunde" button
- Fixed background with dot pattern

### 5. **About Section ("Über uns")**
- Two-column layout
- Left: Text content about CorePulse history (since 2015)
- Right: Placeholder image with gradient background
- CTA button to services

### 6. **Services Section**
- Section title: "Unsere Services"
- 4 service cards:
  1. Personal Training (Running icon) - ab 80€/Stunde
  2. Gruppenkurse (Users icon) - 25€/Kurs  
  3. Ernährungsberatung (Apple icon) - 120€/Beratung
  4. Wellness & Recovery (Spa icon) - ab 40€/Session

### 7. **Testimonials Section ("Bewertungen")**
- Dark background section
- 3 testimonial cards with user avatars
- Customer reviews from Sarah M., Michael K., Lisa B.

### 8. **Contact Section**
- Two-column layout
- Left: Contact information (address, phone, email, hours)
- Right: Contact form with fields (name, email, subject, message)
- Address: Fitness Straße 123, 12345 Musterstadt
- Phone: +49 123 456 789
- Email: info@corepulse.de

### 9. **Footer**
- Dark background
- 4-column layout:
  1. CorePulse description
  2. Quick Links navigation
  3. Services links
  4. Contact information
- Social media icons (Facebook, Instagram, Twitter, YouTube)
- Copyright notice

## 🎨 Color Palette

### Primary Colors
```css
--primary-color: #ff6b35        /* Orange/Red primary */
--secondary-color: #1a1a1a      /* Dark gray/black */
--accent-color: #f7b801         /* Golden yellow */
```

### Text Colors
```css
--text-light: #ffffff           /* White text */
--text-dark: #333333           /* Dark gray text */
--text-gray: #666666           /* Medium gray text */
```

### Background Colors
```css
--bg-light: #f8f9fa            /* Light gray background */
--bg-dark: #1a1a1a             /* Dark background */
```

### Gradients
```css
--gradient-primary: linear-gradient(135deg, #ff6b35 0%, #f7b801 100%)
--gradient-dark: linear-gradient(135deg, #1a1a1a 0%, #333333 100%)
```

### Shadows
```css
--shadow-light: 0 10px 30px rgba(0, 0, 0, 0.1)
--shadow-heavy: 0 20px 60px rgba(0, 0, 0, 0.3)
```

## 🔤 Typography

### Font Families
1. **Primary Font**: 'Inter', sans-serif
   - Used for body text, navigation, buttons
   - Weights: 300, 400, 500, 600, 700

2. **Display Font**: 'Playfair Display', serif
   - Used for headings, logo
   - Weights: 400, 500, 600, 700

### Font Sizes
- Hero headline: 4rem (mobile: 2.5rem)
- Section headings: 3rem (mobile: 2rem)
- Parallax heading: 3.5rem (mobile: 2.5rem)
- About heading: 2.5rem
- Logo: 2rem
- Feature icons: 3rem
- Service icons: 4rem

## 🖼️ Images & Icons

### External Libraries
- **Font Awesome 6.4.0**: All icons throughout the site
- **AOS (Animate On Scroll)**: Animation library

### Image Sources
All images are embedded as SVG data URIs:

1. **Hero Background**: 
   - SVG gradient pattern (orange to yellow)
   - Polygon overlay for visual interest

2. **About Section Image**:
   - SVG placeholder with gradient background
   - Text overlay "Fitness"
   - Dimensions: 400x300px

3. **Parallax Background**:
   - Dark background with dot pattern
   - Created with SVG pattern fill

### Icon Usage
- **Navigation**: Chevron down for scroll indicator
- **Features**: Dumbbell, user-friends, clock, heart, users, mobile
- **Services**: Running, users, apple, spa
- **Contact**: Map marker, phone, envelope, clock
- **Social**: Facebook, Instagram, Twitter, YouTube
- **Testimonials**: User avatar icons

## 📱 Responsive Design

### Breakpoints
- Mobile: max-width: 768px
- Desktop: Default styles

### Mobile Adaptations
- Navigation becomes hamburger menu
- Hero text sizes reduced
- Grid layouts become single column
- Button stacking changes to vertical
- Container padding adjusts

## 🎯 Interactive Elements

### Animations
- Fade-in on scroll (AOS library)
- Hero content sequential animation
- Hover effects on cards and buttons
- Parallax scrolling effects
- Button loading states
- Navbar scroll effects

### JavaScript Features
- Smooth scrolling navigation
- Form validation and submission
- Mobile menu toggle
- Scroll-triggered navbar styling
- Parallax background movement
- Button click animations
- Intersection observer for animations

## 📋 Technical Structure

### HTML Structure
- Semantic HTML5 elements
- Proper heading hierarchy (h1, h2, h3)
- Accessible form labels
- External library integration
- Meta tags for SEO

### CSS Architecture
- CSS Custom Properties (variables)
- Mobile-first responsive design
- Flexbox and CSS Grid layouts
- Modern CSS features (backdrop-filter, object-fit)
- Smooth transitions and animations

### External Dependencies
1. Google Fonts (Inter, Playfair Display)
2. Font Awesome 6.4.0 (icons)
3. AOS 2.3.1 (scroll animations)

This analysis covers the complete structure, visual design, and technical implementation of the CorePulse fitness studio website.