---
name: Vivid Radiance
colors:
  surface: '#fbf9f7'
  surface-dim: '#dbdad8'
  surface-bright: '#fbf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f1'
  surface-container: '#efedec'
  surface-container-high: '#eae8e6'
  surface-container-highest: '#e4e2e0'
  on-surface: '#1b1c1b'
  on-surface-variant: '#5b3f43'
  inverse-surface: '#30302f'
  inverse-on-surface: '#f2f0ee'
  outline: '#8f6f73'
  outline-variant: '#e4bdc2'
  surface-tint: '#bc004b'
  primary: '#b80049'
  on-primary: '#ffffff'
  primary-container: '#e2165f'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb2be'
  secondary: '#9a25ae'
  on-secondary: '#ffffff'
  secondary-container: '#ed76fd'
  on-secondary-container: '#69007a'
  tertiary: '#705d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c9a900'
  on-tertiary-container: '#4c3f00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9de'
  primary-fixed-dim: '#ffb2be'
  on-primary-fixed: '#400014'
  on-primary-fixed-variant: '#900038'
  secondary-fixed: '#ffd6fe'
  secondary-fixed-dim: '#f9abff'
  on-secondary-fixed: '#35003f'
  on-secondary-fixed-variant: '#7b008f'
  tertiary-fixed: '#ffe16d'
  tertiary-fixed-dim: '#e9c400'
  on-tertiary-fixed: '#221b00'
  on-tertiary-fixed-variant: '#544600'
  background: '#fbf9f7'
  on-background: '#1b1c1b'
  surface-variant: '#e4e2e0'
  peach-warmth: '#FFCCBC'
  deep-onyx: '#1A1A1A'
  cream-surface: '#FDFBF9'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

This design system is engineered for a high-energy, premium beauty environment. The brand personality is **glamorous, empowering, and sophisticated**, designed to appeal to a modern clientele that views hair styling as an act of self-expression and confidence.

The visual direction follows a **High-Contrast Modern** style. It rejects the clinical "white-walled" salon aesthetic in favor of a vibrant, fashion-forward approach. The design balances intense, saturated colors with expansive white space and "cream" breathing zones to maintain an upscale feel. The result is an interface that feels energetic and alive, avoiding "infantile" softness by using sharp editorial typography and deep, deliberate contrast.

## Colors

The palette is anchored by **Bold Fuchsia** as the primary driver of action, symbolizing energy and passion. **Vibrant Purple** serves as the sophisticated secondary, used for depth and luxury accents. 

**Application Strategy:**
- **Primary Action:** Use Fuchsia (#E91E63) for key conversion points and primary brand marks.
- **Accents:** Gold (#FFD700) is reserved for "premium" indicators, such as loyalty status, master-stylist badges, or decorative borders.
- **Backgrounds:** Utilize "Cream Surface" (#FDFBF9) as the default canvas to keep the interface warm and inviting. Toggle to full-bleed Fuchsia or Purple sections with white text to create dramatic "editorial" breaks in the scroll.
- **Peach:** Use Peach (#FFCCBC) as a low-intensity background for cards or informational callouts to soften the high-contrast transitions.

## Typography

The typography strategy relies on the tension between a **Classical Serif** (Playfair Display) and a **Geometric Sans-Serif** (Montserrat).

- **Headlines:** Always use Playfair Display. For large display titles, use bold weights with tighter letter spacing to evoke high-fashion magazine mastheads.
- **Body Text:** Montserrat provides a clean, neutral counterpoint. Ensure generous line heights (1.5 - 1.6) to maintain readability against vibrant backgrounds.
- **Labels & Buttons:** Use Montserrat in All-Caps with increased letter-spacing (0.1em) for functional elements to create a sense of professional precision.

## Layout & Spacing

The design system utilizes a **Fluid Grid** with oversized margins to reinforce the "premium" feel. Space is treated as a luxury.

- **Grid:** 12-column layout for desktop; 4-column layout for mobile.
- **Vertical Rhythm:** Use increments of 8px. Sections should be separated by large padding (80px - 120px) to allow each "style" or "service" to breathe.
- **Containment:** Content should be centered within a 1280px container, but vibrant background colors should bleed to the edge of the viewport to create an immersive experience.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** rather than heavy shadows.

- **Surfaces:** Use "Cream Surface" as the base. Elevated elements like cards should use white (#FFFFFF) with a very soft, diffused shadow (15% opacity of the secondary Purple) to give a "lifting" effect without looking heavy.
- **Glassmorphism:** For overlays, mobile menus, or navigation bars, use a backdrop blur (20px) with 80% opacity of the background color. This maintains the "glamorous" feel while ensuring text legibility.
- **Depth:** Elements shouldn't feel "stuck" to the page. Use subtle Y-axis offsets in shadows to suggest they are floating gracefully.

## Shapes

The shape language is **Fluid and Rounded**. This reflects the "glow" and "flow" of hair styling while maintaining professional structure.

- **Standard Radius:** 0.5rem (8px) for buttons and inputs.
- **Large Radius:** 1rem (16px) for service cards and image containers.
- **Circular Elements:** Use pill-shaped buttons for "Book Now" CTAs to make them feel more tactile and inviting.
- **Images:** All imagery should feature soft rounded corners to prevent the high-contrast colors from feeling too aggressive or "sharp."

## Components

### Buttons
- **Primary:** Solid Fuchsia with white text. Pill-shaped. On hover, transition to a Purple gradient.
- **Secondary:** Transparent with a 2px Fuchsia border. All-caps Montserrat text.
- **Accent:** Gold background with Deep Onyx text for "Special Offers" or "VIP Services."

### Cards
- Service cards use a white background with a 16px corner radius. Include a subtle "Peach" top-border or icon accent to link back to the brand palette.
- Hover states for cards should involve a slight scale up (1.02) and a deepening of the soft purple shadow.

### Input Fields
- Use a soft "Cream" fill with a 1px border that turns Fuchsia on focus.
- Floating labels using Montserrat Bold (12px) to keep the form compact and elegant.

### Chips & Tags
- Used for service categories (e.g., "Coloring," "Styling"). 
- Semi-transparent Fuchsia backgrounds with 60% opacity and bold Fuchsia text.

### Navigation
- Sticky header with a backdrop blur. Use the Gold accent color for the active link state or a bottom-border underline.