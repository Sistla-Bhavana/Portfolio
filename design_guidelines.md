# Portfolio Website Design Guidelines

## Design Approach
**Reference-Based**: Drawing inspiration from Stripe's clean aesthetic and GitHub's portfolio templates, focusing on professional minimalism with strategic use of animation and color.

## Color System
The user has specified colors - use exactly as provided:
- **Primary**: #0F172A (slate dark) - Headers, important text
- **Secondary**: #1E293B (slate grey) - Section backgrounds, cards
- **Accent**: #3B82F6 (blue) - CTAs, links, highlights, hover states
- **Background**: #FFFFFF (white) - Main background
- **Text**: #334155 (slate) - Body text
- **Highlight**: #F1F5F9 (light slate) - Subtle backgrounds, borders

**Dark Mode**: Invert the palette maintaining the same color relationships.

## Typography
- **Primary Font**: Inter for body text and UI elements
- **Secondary Font**: Poppins for headings and emphasis
- **Scale**: 
  - Hero/H1: 48px-64px (Poppins Bold)
  - H2: 36px-48px (Poppins SemiBold)
  - H3: 24px-30px (Poppins Medium)
  - Body: 16px-18px (Inter Regular)
  - Small: 14px (Inter Regular)

## Layout System
**Spacing Grid**: 24px base unit (Tailwind: p-6, m-6, gap-6)
- Sections: py-16 to py-24
- Cards: p-6 to p-8
- Element spacing: gap-6, space-y-6
- Container: max-w-6xl mx-auto

## Component Library

### Hero Section
- Full-width section (not 100vh) with professional headshot or abstract gradient background
- Large typography introducing Bhavana as ML/Software Engineer
- Brief tagline highlighting Python, AI/ML, and backend expertise
- Primary CTA: "View Projects" + Secondary: "Download Resume"
- If using image background: blur backdrop for buttons with variant="outline"

### About Section
- Two-column layout (desktop): Left - professional photo/illustration, Right - summary text
- Include education timeline with CGPA highlights
- Contact information displayed as interactive cards (email, phone, LinkedIn, GitHub)
- Smooth fade-in animation on scroll

### Projects Showcase
- Grid layout: 1 column (mobile), 2 columns (tablet), 3 columns (desktop)
- Each project card includes:
  - Project title (Poppins SemiBold)
  - Tech stack badges with accent color
  - Key achievements/metrics (98.6% accuracy, etc.)
  - "View Details" link with arrow icon
- Hover effect: Lift card slightly (translate-y-2), add subtle shadow
- Gradient border accent on hover

### Experience & Certifications
- Timeline or card-based layout
- Deloitte internship highlighted prominently
- Certification cards with provider logos/icons
- Date ranges displayed clearly
- Stagger animation on scroll reveal

### Skills Section
- Organized by categories matching resume structure
- Animated skill tags with accent background on hover
- Grid layout for balanced distribution
- Icons from Heroicons for visual interest
- Smooth tag appearance animations

### Contact Section
- Clean form layout OR prominent contact card grid
- Direct links to email, LinkedIn, GitHub
- Phone number with call-to-action
- Location displayed subtly
- Accent color for interactive elements

## Animations & Transitions
**Keep Subtle and Professional**:
- Fade-in on scroll: 0.6s ease-out
- Hover transitions: 0.3s ease
- Card lifts: translate-y-2
- Smooth page navigation (if multi-page)
- Avoid excessive motion - prioritize performance

## Images
**Hero Section**: Yes - use a professional abstract background or gradient overlay (blue to slate gradient) rather than a large photo
**About Section**: Include a professional headshot or illustration in circular frame
**Project Cards**: Optional thumbnail images for each project showing UI/results
**Certifications**: Provider logos (AWS, NPTEL, etc.) as small icons

All images should have proper aspect ratios, lazy loading, and fallback backgrounds.

## Responsive Behavior
- Mobile: Single column, stacked sections, hamburger menu
- Tablet: 2-column grids, adjusted spacing
- Desktop: Full multi-column layouts, hover states active
- Breakpoints: sm (640px), md (768px), lg (1024px), xl (1280px)

## Accessibility
- WCAG AA contrast ratios maintained
- Focus states visible on all interactive elements
- Semantic HTML structure
- Alt text for all images
- Keyboard navigation support

## Key Design Principles
1. **Professional First**: Clean, trustworthy, showcasing technical expertise
2. **Content Hierarchy**: Resume achievements prominently displayed
3. **Smooth Experience**: Subtle animations enhance, never distract
4. **Mobile Excellence**: Fully functional and beautiful on small screens
5. **Performance**: Fast load times, optimized assets