# AIYUBOT Marketplace - Landing Page Specification

## 1. Project Overview
- **Project Name**: AIYUBOT Marketplace
- **Type**: Premium AI platform landing page
- **Core Functionality**: Showcase AI agent marketplace with premium UI/UX
- **Target Users**: Tech companies, developers, businesses seeking AI agents

## 2. UI/UX Specification

### Design Philosophy
- **Style**: Futuristic 2025+ with glassmorphism and neon accents
- **Feel**: Premium, high-tech, innovative
- **Inspiration**: OpenAI, Anthropic, premium SaaS platforms

### Color Palette
```css
--bg-primary: #0a0a0f
--bg-secondary: #12121a
--bg-card: rgba(255, 255, 255, 0.03)
--bg-glass: rgba(255, 255, 255, 0.05)
--accent-primary: #8b5cf6 (violet)
--accent-secondary: #06b6d4 (cyan)
--accent-tertiary: #f472b6 (pink)
--accent-gradient: linear-gradient(135deg, #8b5cf6, #06b6d4, #f472b6)
--text-primary: #ffffff
--text-secondary: rgba(255, 255, 255, 0.7)
--text-muted: rgba(255, 255, 255, 0.4)
--border-glow: rgba(139, 92, 246, 0.3)
--glow-violet: 0 0 30px rgba(139, 92, 246, 0.4)
--glow-cyan: 0 0 30px rgba(6, 182, 212, 0.4)
```

### Typography
- **Headings**: "Syne", sans-serif (bold, modern)
- **Body**: "DM Sans", sans-serif (clean, readable)
- **Hero Title**: 72px (desktop), 40px (mobile)
- **Section Titles**: 48px (desktop), 32px (mobile)
- **Body Text**: 18px
- **Small Text**: 14px

### Layout Structure

#### Hero Section
- Full viewport height with animated gradient mesh background
- Floating animated gradient orbs (3-4 blobs)
- Main headline with gradient text effect
- Tagline with typewriter or fade animation
- Two CTA buttons with glow effects
- Floating AI agent cards (3 cards with tilt animation)
- Particle/grid background animation

#### Featured AI Agents Section
- Asymmetrical grid layout (not simple cards)
- Cards with glassmorphism effect
- Hover: scale + glow + gradient border
- Staggered entrance animation
- Categories: Code Assistant, Data Analyst, Customer Support, Creative Writer

#### How It Works Section
- Horizontal timeline with animated connections
- Steps: Browse → Select → Deploy → Scale
- Each step has floating icon with pulse animation
- Connecting line with animated gradient

#### Categories Section
- Interactive pill/chip style navigation
- Glassmorphism background cards
- Hover: gradient border + slight lift
- Categories: Development, Business, Creative, Analytics, Security

#### Why Choose Us Section
- Modern split layout with floating elements
- Animated statistics counter
- Feature cards with icon glow
- Parallax floating shapes in background

#### CTA Section
- Full-width gradient mesh background
- Large headline with gradient text
- Email input + button combo
- Floating background elements

#### Footer
- Minimal design with glassmorphism
- Logo, links, social icons
- Gradient border top

### Animations & Interactions

#### Global
- Custom cursor with glow trail
- Smooth scroll behavior
- Intersection Observer for reveal animations

#### Specific Animations
1. **Hero gradient orbs**: Floating infinite animation (20-30s)
2. **Glass cards**: Subtle floating on hover
3. **Buttons**: Scale 1.05 + glow intensity increase on hover
4. **Section reveals**: Fade up + stagger
5. **Cursor**: Follow with blur glow effect
6. **Background**: Subtle parallax on scroll

### Responsive Breakpoints
- Desktop: > 1200px
- Tablet: 768px - 1200px
- Mobile: < 768px

## 3. Functionality Specification

### Core Features
- Animated hero with gradient background
- Featured AI agent cards with hover effects
- Interactive category selection
- Animated "How It Works" timeline
- Statistics counter animation
- Newsletter signup form (visual only)
- Smooth scroll navigation

### User Interactions
- Cursor follows with glow
- Hover states on all interactive elements
- Scroll-triggered animations
- Category filtering (visual)
- Smooth anchor scrolling

### Edge Cases
- Graceful degradation for older browsers
- Fallback for reduced motion preference

## 4. Acceptance Criteria

### Visual Checkpoints
- [ ] Hero has animated gradient background with floating orbs
- [ ] Typography uses Syne for headings, DM Sans for body
- [ ] Glassmorphism effect visible on cards
- [ ] All buttons have glow effect on hover
- [ ] Custom cursor with glow trail works
- [ ] Sections have staggered reveal animations
- [ ] Responsive on mobile/tablet/desktop

### Performance Checkpoints
- [ ] Smooth 60fps animations
- [ ] No layout shift on load
- [ ] Fonts load correctly
- [ ] No console errors

### Code Quality
- [ ] Single HTML file with embedded CSS/JS
- [ ] CSS variables for theming
- [ ] Clean, organized code structure
- [ ] No external frameworks