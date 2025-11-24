# Democratic Clarity Design System

## Overview

A comprehensive design system for political analysis presentations targeting Danish high school students (STX 3.g level). The system balances **academic credibility** with **modern visual storytelling** to convey authority, intellectual rigor, and political neutrality while maintaining engagement.

---

## Design Philosophy

### Primary Emotion
**Informed Confidence** - Users should feel intellectually empowered, politically engaged, and analytically sharp.

### Visual Aesthetic
**Modern Academic Professional** - Clean, data-driven, with subtle Danish political heritage cues.

### Target Audience
Politically engaged Danish youth (16-19 years old) studying at STX gymnasium level with interest in samfundsfag (social science), politics, and democratic processes.

### Brand Personality
- Intellectually Rigorous (not stuffy)
- Politically Engaged (not biased)
- Youth-Forward (not trendy)
- Data-Driven (not overwhelming)
- Danish Heritage (not nationalistic)

---

## Color Palette

### Primary Colors

#### Democratic Blue
- **Hex:** `#1E3A8A`
- **RGB:** `30, 58, 138`
- **Usage:** Headers, primary navigation, key data points, call-to-action buttons
- **Meaning:** Trust, stability, institutional authority, democratic process
- **Accessibility:** WCAG AA compliant with white text

#### Parliament Red
- **Hex:** `#DC2626`
- **RGB:** `220, 38, 38`
- **Usage:** Accent elements, emphasis, important statistics, Danish flag heritage
- **Meaning:** Democratic energy, engagement, Danish national identity
- **Accessibility:** WCAG AA compliant with white text

### Secondary Colors

#### Slate Gray
- **Hex:** `#334155`
- **RGB:** `51, 65, 85`
- **Usage:** Body text, secondary headings, neutral information
- **Meaning:** Professional, neutral, serious analysis

#### Soft White
- **Hex:** `#F8FAFC`
- **RGB:** `248, 250, 252`
- **Usage:** Background, cards, content containers
- **Meaning:** Clean, spacious, accessible

### Accent Colors

#### Data Teal
- **Hex:** `#0D9488`
- **RGB:** `13, 148, 136`
- **Usage:** Charts representing left-wing parties (SF, Enhedslisten)

#### Economic Amber
- **Hex:** `#D97706`
- **RGB:** `217, 119, 6`
- **Usage:** Economic data, center-right party indicators (Venstre, Liberal Alliance)

#### Neutral Beige
- **Hex:** `#78716C`
- **RGB:** `120, 113, 108`
- **Usage:** Tertiary information, metadata, timestamps, source citations

### Semantic Colors

#### Success Green
- **Hex:** `#10B981`
- **RGB:** `16, 185, 129`
- **Usage:** Positive trends, election victories, growth indicators

#### Warning Yellow
- **Hex:** `#F59E0B`
- **RGB:** `245, 158, 11`
- **Usage:** Caution, volatility warnings, dealignment indicators

#### Error Red
- **Hex:** `#EF4444`
- **RGB:** `239, 68, 68`
- **Usage:** Negative trends, decline indicators, errors

#### Info Blue
- **Hex:** `#3B82F6`
- **RGB:** `59, 130, 246`
- **Usage:** Informational callouts, neutral statistics, educational content

---

## Typography System

### Font Families

#### Primary: Inter
```css
font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
```
- **CDN:** Google Fonts
- **Weights Used:** 400 (Regular), 500 (Medium), 600 (SemiBold), 700 (Bold)
- **Rationale:** Modern, highly legible, excellent for data-heavy content, neutral political stance
- **Character:** Professional, accessible, clean
- **Primary Usage:** All UI elements, body text, data labels, navigation, tables

#### Display: Playfair Display
```css
font-family: 'Playfair Display', Georgia, serif;
```
- **CDN:** Google Fonts
- **Weights Used:** 700 (Bold)
- **Rationale:** Adds gravitas and academic authority
- **Character:** Classical, authoritative, refined
- **Limited Usage:** Main page title (h1) only

### Type Scale & Specifications

| Element | Size | Weight | Line Height | Letter Spacing | Color | Usage |
|---------|------|--------|-------------|----------------|-------|-------|
| **H1** | 48px (3rem) | 700 | 1.2 | -0.02em | Democratic Blue | Page titles |
| **H2** | 36px (2.25rem) | 600 | 1.3 | -0.01em | Democratic Blue | Section headers |
| **H3** | 24px (1.5rem) | 600 | 1.4 | 0em | Slate Gray | Subsections |
| **H4** | 20px (1.25rem) | 600 | 1.5 | 0em | Slate Gray | Card titles |
| **Body Large** | 18px (1.125rem) | 400 | 1.6 | 0em | Slate Gray | Introductions |
| **Body Regular** | 16px (1rem) | 400 | 1.6 | 0em | Slate Gray | Main content |
| **Body Small** | 14px (0.875rem) | 400 | 1.5 | 0em | Slate Gray | Supporting text |
| **Caption** | 12px (0.75rem) | 500 | 1.4 | 0.02em | Neutral Beige | Metadata |
| **Data Label** | 14px (0.875rem) | 600 | 1.4 | 0.05em | Slate Gray | Chart labels |
| **Stat Highlight** | 48px (3rem) | 700 | 1.0 | 0em | Parliament Red | Key statistics |

### Typography Guidelines

#### DO:
- Use Inter for 95% of content
- Maintain minimum 16px body text for accessibility (WCAG AA)
- Use bold weights (600-700) sparingly for hierarchy
- Keep line length between 60-75 characters for optimal readability
- Use proper semantic HTML (h1, h2, h3, p, strong)
- Ensure sufficient contrast ratios (4.5:1 minimum for normal text)

#### DON'T:
- Mix more than 2 font families in a single view
- Use font sizes below 12px
- Create more than 4 levels of hierarchy per screen
- Use ALL CAPS for body text (acceptable for labels/tags only)
- Use decorative fonts for data-heavy content
- Stack multiple bold elements without spacing

---

## Spacing & Grid System

### Base Unit: 4px
All spacing increments based on 4px multiples (0.25rem) for visual consistency and mathematical precision.

### Spacing Scale

```css
--space-xs:  4px   (0.25rem)  /* Tight internal spacing */
--space-sm:  8px   (0.5rem)   /* Small gaps */
--space-md:  16px  (1rem)     /* Standard spacing */
--space-lg:  24px  (1.5rem)   /* Section spacing */
--space-xl:  32px  (2rem)     /* Major sections */
--space-2xl: 48px  (3rem)     /* Slide sections */
--space-3xl: 64px  (4rem)     /* Dramatic separation */
```

### Application Guidelines

| Spacing Type | Size | Usage |
|-------------|------|-------|
| **xs (4px)** | Inline elements | Icon-to-text, tag spacing |
| **sm (8px)** | Close relationships | List item spacing, inline groups |
| **md (16px)** | Paragraph spacing | Between paragraphs, card internal padding |
| **lg (24px)** | Content blocks | Between cards, table margins |
| **xl (32px)** | Major sections | Slide padding, component groups |
| **2xl (48px)** | Slide structure | Between major slide sections |
| **3xl (64px)** | Dramatic emphasis | Special highlighted sections |

### Grid System

#### Desktop (1025px+)
- **12-column grid** with 24px gutters
- **Max content width:** 1280px (centered)
- **Side margins:** 32px minimum

#### Tablet (641-1024px)
- **8-column grid** with 20px gutters
- **Adaptive layouts:** 2-3 column content blocks
- **Side margins:** 24px minimum

#### Mobile (0-640px)
- **4-column grid** with 16px gutters
- **Single column layout** for content
- **Side margins:** 16px minimum

### Layout Principles

#### Vertical Rhythm
- Maintain consistent vertical spacing using the 4px base unit
- **48px spacing** between major sections
- **24px spacing** between related content blocks
- **16px spacing** between paragraphs

#### Horizontal Structure
- Content should never touch screen edges
- Minimum 16px padding on mobile
- Maximum 1280px content width for readability
- Center-align content containers

---

## Component Library

### 1. Slide Container

**Purpose:** Main content wrapper for each presentation slide

```css
.slide {
  width: 100%;
  max-width: 1280px;
  margin: 0 auto;
  padding: 32px;
  min-height: 100vh;
  background: #F8FAFC;
}
```

**Specifications:**
- Max width: 1280px
- Padding: 32px all sides (24px on tablet, 16px on mobile)
- Min height: 100vh (full viewport)
- Background: Soft White (#F8FAFC)

**Usage Rules:**
- Each slide should contain 1 main idea
- Maximum 3 major content blocks per slide
- Include slide number in bottom right corner
- Maintain consistent padding across all slides

**DO:**
- Use consistent padding
- Maintain vertical rhythm with 24-48px spacing
- Keep content centered and balanced

**DON'T:**
- Overcrowd with more than 3 major blocks
- Use competing background colors
- Exceed 100vh without scroll indication
- Mix different padding values

---

### 2. Data Cards

**Purpose:** Display statistical information, theory explanations, and case studies with visual hierarchy

```css
.data-card {
  background: #FFFFFF;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
  border-left: 4px solid #1E3A8A;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  margin-bottom: 24px;
}

.data-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}
```

**Variants:**

| Class | Border Color | Usage |
|-------|-------------|-------|
| `.data-card` (default) | Democratic Blue (#1E3A8A) | Standard information |
| `.data-card--success` | Success Green (#10B981) | Positive trends, victories |
| `.data-card--warning` | Economic Amber (#D97706) | Caution, economic data |
| `.data-card--info` | Info Blue (#3B82F6) | Educational, neutral facts |

**Interactive States:**
- **Hover:** Elevates 2px with enhanced shadow
- **Focus:** 2px solid outline (#DC2626)
- **Active:** Slight scale down (0.98)

**DO:**
- Use semantic color variants appropriately
- Include clear headings (h3 or h4)
- Maintain 24px internal padding
- Group related cards with 24px spacing

**DON'T:**
- Stack more than 3 cards without visual break
- Use cards for single-line content
- Override border-left styling
- Nest cards within cards

---

### 3. Comparison Tables

**Purpose:** Side-by-side comparisons of data, theories, or case studies (København vs. Næstved, KV vs. FV)

```css
.comparison-table {
  width: 100%;
  border-collapse: separate;
  border-spacing: 0;
  background: #FFFFFF;
  border-radius: 8px;
  overflow: hidden;
  margin: 24px 0;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
}

.comparison-table th {
  background: #1E3A8A;
  color: #FFFFFF;
  padding: 16px;
  font-weight: 600;
  text-align: left;
}

.comparison-table td {
  padding: 16px;
  border-bottom: 1px solid #E2E8F0;
}
```

**Specifications:**
- Header background: Democratic Blue
- Alternating row colors: White / Soft White
- Cell padding: 16px
- Border radius: 8px
- Font size: 16px (body regular)

**DO:**
- Use clear, concise headers
- Align text left for readability
- Maintain consistent cell padding
- Include at least 2 comparison columns

**DON'T:**
- Use more than 4 columns on mobile
- Mix text alignment styles
- Overcrowd cells with dense text
- Use tables for non-comparative data

---

### 4. Theory Tags

**Purpose:** Quick visual identification of political theories being referenced

```css
.theory-tag {
  display: inline-block;
  padding: 6px 12px;
  border-radius: 16px;
  font-size: 14px;
  font-weight: 600;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  margin: 4px;
}
```

**Variants:**

| Tag | Background | Text Color | Theory |
|-----|-----------|-----------|--------|
| `.theory-tag--michigan` | #DBEAFE | #1E3A8A | Michigan Model |
| `.theory-tag--downs` | #FEF3C7 | #92400E | Rational Choice (Downs) |
| `.theory-tag--cleavage` | #D1FAE5 | #065F46 | Cleavage Theory |
| `.theory-tag--agenda` | #FCE7F3 | #9F1239 | Agenda-Setting |
| `.theory-tag--inglehart` | #E0E7FF | #3730A3 | Value Shift (Inglehart) |

**Usage Context:**
- Place at start of sections referencing theory
- Group multiple tags with 4px spacing
- Always pair with explanatory text

**DO:**
- Use consistent color-theory associations
- Keep text concise (1-2 words)
- Place before related content

**DON'T:**
- Use more than 3 tags per content block
- Create custom colors outside system
- Use as standalone elements

---

### 5. Quote Blocks

**Purpose:** Highlight expert quotes, politician statements, or significant commentary

```css
.quote-block {
  border-left: 4px solid #DC2626;
  padding: 24px 24px 24px 32px;
  background: linear-gradient(90deg, #FEE2E2 0%, #F8FAFC 100%);
  font-style: italic;
  margin: 32px 0;
  border-radius: 0 8px 8px 0;
}

.quote-block cite {
  display: block;
  margin-top: 16px;
  font-style: normal;
  font-weight: 600;
  color: #334155;
  font-size: 14px;
}

.quote-block cite::before {
  content: "— ";
}
```

**Specifications:**
- Border left: 4px Parliament Red
- Gradient background: Red tint to Soft White
- Italic text for quote body
- Normal text for citation
- 32px top/bottom margins

**DO:**
- Attribute quotes with full name and title
- Keep quotes concise (1-3 sentences)
- Use for authoritative sources

**DON'T:**
- Use for general text emphasis
- Stack quotes without spacing
- Omit citation information
- Paraphrase within quote blocks

---

### 6. Political Spectrum Visualizer

**Purpose:** Interactive horizontal axis showing Danish political party positions

```css
.spectrum-line {
  height: 4px;
  background: linear-gradient(90deg, #DC2626 0%, #1E3A8A 100%);
  border-radius: 2px;
  position: relative;
  margin: 24px 0;
}

.party-marker {
  position: absolute;
  top: -8px;
  transform: translateX(-50%);
  font-weight: 700;
  font-size: 16px;
  padding: 8px 12px;
  background: #FFFFFF;
  border: 2px solid #1E3A8A;
  border-radius: 20px;
  cursor: pointer;
  transition: all 0.2s ease;
}

.party-marker:hover {
  transform: translateX(-50%) scale(1.1);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
}
```

**Party Positions (left to right):**
- Enhedslisten (Ø): 15%
- SF: 25%
- Socialdemokratiet (S): 40%
- Venstre (V): 60%
- Konservative (K): 75%
- Liberal Alliance (LA): 85%

**Interactive Features:**
- Hover: Scale 1.1x with shadow
- Click: Potential filtering functionality
- Median indicator: Shows theoretical median voter

---

### 7. Navigation System

#### Navigation Arrows

```css
.nav-arrow {
  position: fixed;
  bottom: 48px;
  width: 56px;
  height: 56px;
  border-radius: 50%;
  background: #1E3A8A;
  color: #FFFFFF;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  transition: all 0.2s ease;
}

.nav-arrow:hover {
  background: #DC2626;
  transform: scale(1.1);
}
```

**Positioning:**
- Left arrow: 32px from left edge
- Right arrow: 32px from right edge
- Both: 48px from bottom

**States:**
- Default: Democratic Blue
- Hover: Parliament Red with scale(1.1)
- Disabled: Opacity 0.5

#### Slide Counter

```css
.slide-counter {
  position: fixed;
  bottom: 48px;
  left: 50%;
  transform: translateX(-50%);
  background: rgba(255, 255, 255, 0.95);
  padding: 12px 24px;
  border-radius: 24px;
  font-weight: 600;
  font-size: 14px;
}
```

**Format:** "1 / 14" (current / total)

#### Keyboard Navigation
- **→ or Space:** Next slide
- **←:** Previous slide
- **Home:** First slide
- **End:** Last slide

#### Click Navigation
- **Right 60% of screen:** Next slide
- **Left 40% of screen:** Previous slide

#### Touch Navigation
- **Swipe left:** Next slide
- **Swipe right:** Previous slide
- **Minimum swipe distance:** 50px

---

## Animation & Interaction Patterns

### 1. Slide Transitions

```css
@keyframes slideInFromRight {
  from {
    opacity: 0;
    transform: translateX(30px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

.slide {
  animation: slideInFromRight 0.4s cubic-bezier(0.16, 1, 0.3, 1);
}
```

**Duration:** 400ms  
**Easing:** cubic-bezier(0.16, 1, 0.3, 1) - "ease-out-expo"  
**Effect:** Smooth directional entry suggesting forward progression

---

### 2. Card Hover Effects

```css
.data-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}
```

**Duration:** 200ms  
**Easing:** ease  
**Effect:** Subtle lift creating depth and interactivity

---

### 3. Animated Statistics

JavaScript-powered count-up animation for key statistics:

```javascript
function animateValue(element, start, end, duration, suffix = '') {
  const range = end - start;
  const increment = range / (duration / 16);
  let current = start;
  
  const timer = setInterval(() => {
    current += increment;
    if (current >= end) {
      current = end;
      clearInterval(timer);
    }
    element.textContent = Math.floor(current) + suffix;
  }, 16);
}
```

**Trigger:** Intersection Observer when slide becomes active  
**Duration:** 1000ms  
**Framerate:** 60fps (16ms intervals)  
**Use cases:** Percentages, large numbers, impact statistics

---

### 4. Button State Transitions

| State | Transform | Color | Shadow | Duration |
|-------|-----------|-------|--------|----------|
| **Default** | none | Democratic Blue | Light | - |
| **Hover** | scale(1.1) | Parliament Red | Medium | 200ms |
| **Active** | scale(0.95) | Dark Blue | None | 100ms |
| **Focus** | none | Democratic Blue | Outline | - |

---

## Visual Hierarchy Strategy

### Information Architecture

#### Level 1: Primary (Highest Priority)
- **Elements:** Key findings, major statistics, slide titles
- **Typography:** H1 (48px), Stat Highlight (48px), Bold weights
- **Color:** Democratic Blue, Parliament Red
- **Position:** Top third of slide, centered

#### Level 2: Secondary (Supporting Context)
- **Elements:** Explanations, theory descriptions, comparison data
- **Typography:** H2-H3 (36-24px), Body Large (18px)
- **Color:** Slate Gray, Democratic Blue accents
- **Position:** Middle section, left-aligned

#### Level 3: Tertiary (Metadata)
- **Elements:** Sources, footnotes, timestamps, slide numbers
- **Typography:** Caption (12px), Body Small (14px)
- **Color:** Neutral Beige
- **Position:** Bottom of slide, right-aligned

### Reading Patterns

#### Z-Pattern (Text-Heavy Slides)
1. Title (top left)
2. Key statistic (top right)
3. Body content (middle left)
4. Call-to-action (bottom right)

#### F-Pattern (Data Comparison Slides)
1. Header row (full width)
2. Left column (detailed scanning)
3. Right column (selective scanning)
4. Bottom row (final summary)

#### Center-Focused (Theory Diagrams)
1. Central concept (diagram center)
2. Supporting elements (radiating outward)
3. Explanatory text (below diagram)

---

## Accessibility Standards

### WCAG 2.1 AA Compliance

#### Color Contrast Requirements

| Text Type | Size | Contrast Ratio | Example |
|-----------|------|----------------|----------|
| **Normal text** | < 18px | 4.5:1 minimum | Slate Gray on Soft White |
| **Large text** | ≥ 18px or ≥ 14px bold | 3:1 minimum | Democratic Blue on White |
| **UI components** | Any | 3:1 minimum | Buttons, borders |

#### Keyboard Navigation
- ✅ Full presentation controllable without mouse
- ✅ Visible focus indicators (2px solid outline)
- ✅ Logical tab order through interactive elements
- ✅ Arrow keys for slide navigation
- ✅ Home/End keys for jump navigation

#### Screen Reader Support
```html
<main role="main">
  <article class="slide" aria-labelledby="slide-title">
    <header>
      <h1 id="slide-title">Slide Title</h1>
    </header>
    <section aria-label="Main content">
      <!-- Content -->
    </section>
    <footer aria-label="Sources and metadata">
      <!-- Citations -->
    </footer>
  </article>
</main>
```

#### Focus Indicators
```css
:focus {
  outline: 2px solid #DC2626;
  outline-offset: 2px;
}

:focus:not(:focus-visible) {
  outline: none;
}

:focus-visible {
  outline: 2px solid #DC2626;
  outline-offset: 2px;
}
```

---

## Responsive Design

### Breakpoints

| Name | Range | Grid | Padding | Font Scale |
|------|-------|------|---------|------------|
| **Mobile** | 0-640px | 1 column | 16px | 0.875x |
| **Tablet** | 641-1024px | 2-3 columns | 24px | 1x |
| **Desktop** | 1025px+ | 12 columns | 32px | 1x |

### Responsive Typography

```css
@media (max-width: 768px) {
  h1 { font-size: 36px; }  /* from 48px */
  h2 { font-size: 28px; }  /* from 36px */
  h3 { font-size: 20px; }  /* from 24px */
  .stat-highlight { font-size: 36px; }  /* from 48px */
}
```

### Mobile-Specific Adjustments
- Single-column layout for all content
- Larger touch targets (minimum 44x44px)
- Simplified navigation (smaller arrows)
- Hidden keyboard hints
- Vertical table scrolling
- Stacked comparison cards

---

## Implementation Guidelines

### HTML Structure

```html
<!DOCTYPE html>
<html lang="da">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Presentation Title</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
</head>
<body>
  <div class="presentation-container">
    <div class="slide active">
      <!-- Slide content -->
    </div>
  </div>
  
  <div class="nav-arrow nav-arrow--prev">&lsaquo;</div>
  <div class="nav-arrow nav-arrow--next">&rsaquo;</div>
  <div class="slide-counter">1 / 14</div>
</body>
</html>
```

### CSS Organization

1. **Reset & Base Styles**
2. **CSS Variables (Custom Properties)**
3. **Typography System**
4. **Layout Components (Slides, Grids)**
5. **UI Components (Cards, Tables, Tags)**
6. **Interactive Elements (Navigation, Buttons)**
7. **Animations & Transitions**
8. **Responsive Media Queries**

### JavaScript Functionality

**Core Features:**
- Slide navigation system
- Keyboard event handlers
- Touch/swipe detection
- Animated statistics
- Intersection observers for animations

**Performance Considerations:**
- Use `requestAnimationFrame` for smooth animations
- Debounce resize events
- Lazy-load heavy content
- Minimize DOM manipulations

---

## Usage Do's and Don'ts

### Color Usage

✅ **DO:**
- Use Democratic Blue for all primary actions and headers
- Reserve Parliament Red for emphasis and key statistics
- Maintain consistent color-theory associations
- Check contrast ratios before implementation

❌ **DON'T:**
- Use red/blue for non-political meanings
- Mix shades outside the defined palette
- Use color as the only differentiator (accessibility)
- Create gradients between unrelated colors

---

### Typography

✅ **DO:**
- Use semantic HTML (h1, h2, h3)
- Maintain 16px minimum for body text
- Keep line length 60-75 characters
- Use proper weight hierarchy (400, 600, 700)

❌ **DON'T:**
- Use more than 3 font weights per view
- Create artificial boldness with text-stroke
- Stack multiple bold elements without spacing
- Use ALL CAPS extensively

---

### Spacing

✅ **DO:**
- Follow the 4px base unit system
- Use consistent padding across components
- Maintain 24px minimum between content blocks
- Ensure content never touches screen edges

❌ **DON'T:**
- Use arbitrary spacing values (e.g., 17px, 23px)
- Mix rem and px units inconsistently
- Create negative margins without purpose
- Exceed 64px spacing except for dramatic effect

---

### Components

✅ **DO:**
- Use semantic variant classes (--success, --warning)
- Maintain component padding consistency
- Group related components with proper spacing
- Include hover states for interactive elements

❌ **DON'T:**
- Nest cards within cards
- Override core component styles inline
- Mix component types inconsistently
- Create custom variants outside the system

---

### Interactions

✅ **DO:**
- Provide visual feedback within 100ms
- Use smooth easing functions (ease, ease-out)
- Include focus indicators for accessibility
- Support keyboard, mouse, and touch input

❌ **DON'T:**
- Auto-advance slides without user control
- Use animations exceeding 500ms
- Disable pointer events without reason
- Create interactions requiring precise targeting

---

### Data Visualization

✅ **DO:**
- Include source citations on all statistics
- Use appropriate color semantics (green=positive)
- Provide context for all numbers
- Maintain consistent number formatting

❌ **DON'T:**
- Use more than 4 colors per chart
- Present data without units or context
- Omit data sources or timestamps
- Manipulate scales to mislead

---

## Browser Support

### Fully Supported
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Partial Support (Graceful Degradation)
- Internet Explorer 11 (basic functionality only)
- Safari 12-13 (limited CSS features)

### Required Features
- CSS Grid
- CSS Custom Properties (Variables)
- ES6 JavaScript (Arrow functions, const/let)
- Intersection Observer API
- CSS Animations & Transitions

---

## File Structure

```
presentation-design-system/
├── index.html           # Main presentation file
├── DESIGN_SYSTEM.md     # This documentation
├── README.md            # Project overview
└── assets/              # (Optional) External resources
    ├── fonts/          # Local font files
    ├── images/         # Images and graphics
    └── scripts/        # Separated JavaScript
```

---

## Credits & References

### Design Influences
- **Danish Political Aesthetics:** Folketinget branding, Altinget editorial design
- **Academic Presentation Standards:** STX gymnasium presentation guidelines
- **Modern Web Design:** Material Design principles, Tailwind CSS utilities

### Typography Sources
- **Inter:** Rasmus Andersson (Google Fonts)
- **Playfair Display:** Claus Eggers Sørensen (Google Fonts)

### Political Theory References
- Michigan Model (Campbell et al.)
- Rational Choice Theory (Anthony Downs)
- Cleavage Theory (Lipset & Rokkan)
- Agenda-Setting Theory (McCombs & Shaw)
- Value Shift Theory (Ronald Inglehart)

---

## Version History

**v1.0.0** - November 24, 2025
- Initial release
- Complete design system documentation
- Functional presentation with 14 slides
- Full accessibility compliance
- Responsive design implementation

---

## Contact & Contribution

For questions, suggestions, or contributions to this design system:
- **Repository:** https://github.com/ston1ee/presentation-design-system
- **Issues:** Submit via GitHub Issues
- **License:** Open source (specify license as needed)

---

**Last Updated:** November 24, 2025  
**Maintained by:** ston1ee  
**Design System Version:** 1.0.0