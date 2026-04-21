# Frola - Argentine Patisserie Landing Page Specification

## 1. Concept & Vision

Frola is a premium Argentine patisserie specializing in Pasta Frola - the iconic traditional sweet pie with dulce de membrillo (quince paste). The website embodies the warmth of Argentine baking traditions with a sophisticated, artisanal elegance. It feels like walking into a sun-drenched patisserie in Buenos Aires, where heritage meets modern refinement.

**Personality**: Warm, authentic, refined, inviting - a celebration of Argentine baking heritage.

## 2. Design Language

### Aesthetic Direction
Inspired by high-end European patisseries with Argentine soul. Clean layouts with generous whitespace, rich warm colors, and photography that tells a story of tradition and craftsmanship.

### Color Palette
- **Primary Red** (Quince/Crimson): #C41E3A - representing dulce de membrillo
- **Ocre/Golden** (Crust): #D4A84B - warm pastry tones
- **Cream**: #FDF6E9 - soft background warmth
- **Deep Brown**: #2D1810 - rich text and contrast
- **Warm White**: #FFFEF9 - clean sections
- **Soft Blush**: #F5E6D3 - secondary backgrounds

### Typography
- **Display/Headings**: Playfair Display (serif) - elegant, traditional
- **Body**: Inter (sans-serif) - clean, modern readability
- **Accents**: Cormorant Garamond - for elegant callouts

### Spatial System
- Base unit: 8px
- Section padding: 80px - 120px vertical
- Content max-width: 1200px
- Card gaps: 32px

### Motion Philosophy
- Subtle fade-ins on scroll (opacity 0→1, 600ms ease-out)
- Smooth hover transitions (300ms ease)
- Parallax subtle depth on hero
- Scale transforms on interactive elements (1.02x on hover)

### Visual Assets
- Abstract food photography style gradients
- Warm lighting effects
- Organic shapes and soft curves
- Quince/patisserie pattern elements

## 3. Layout & Structure

### Page Flow
1. **Hero Section** - Full viewport, dramatic presentation with video/gradient background
2. **Our Story** - Split layout, image + text, warm narrative
3. **Products Showcase** - Grid of Pasta Frola variants with elegant cards
4. **Values/Quality** - Icon-driven feature section
5. **Contact/Location** - Map integration + contact info
6. **Footer** - Social links, quick navigation

### Responsive Strategy
- Desktop: Full layouts, large typography, horizontal arrangements
- Tablet (768px): Adjusted grids (2 columns), reduced spacing
- Mobile (480px): Single column, stacked layouts, touch-friendly

## 4. Features & Interactions

### Navigation
- Fixed header with subtle background on scroll
- Smooth scroll to sections
- Language toggle (ES/EN) - optional future feature

### Hero Section
- Video background with warm overlay
- Animated headline with stagger effect
- CTA button with hover glow

### Product Cards
- Hover lift effect with shadow
- Image scale on hover (1.05x)
- Quick view overlay possibility

### Contact Section
- Interactive map placeholder
- Form with validation feedback
- Social links with hover animations

## 5. Component Inventory

### Navigation Bar
- Logo left, menu right
- States: default (transparent), scrolled (solid background with shadow)
- Mobile: hamburger menu with slide-out drawer

### Hero Component
- Full viewport container
- Video/image background with color overlay
- Headline, subheadline, CTA group

### Section Headers
- Elegant serif headline
- Optional decorative line element
- Subtle fade-in animation

### Product Cards
- Image container (aspect-ratio 4:3)
- Title, description, price
- Hover: scale + shadow elevation

### Feature Cards (Values)
- Icon (SVG), heading, description
- Arranged in 3-4 column grid
- Subtle hover highlight

### Contact Form
- Input fields with floating labels
- Submit button with loading state
- Success/error message display

### Footer
- Multi-column layout
- Logo, nav links, social icons
- Copyright text

## 6. Technical Approach

### Stack
- Vanilla HTML5, CSS3, JavaScript
- No framework dependencies
- CSS custom properties for theming
- Intersection Observer for scroll animations

### Performance
- Lazy loading for images below fold
- Optimized video encoding
- Minimal external dependencies
- Google Fonts with display=swap

### Accessibility
- Semantic HTML structure
- Alt text for images
- Keyboard navigation support
- Color contrast compliance

### Asset Requirements
- Hero video: 1080p, loop, muted autoplay
- Product images: 800x600 minimum, WebP preferred
- Icons: Inline SVG for performance
- Decorative patterns: CSS gradients/shapes