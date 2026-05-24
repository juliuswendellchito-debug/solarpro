---
name: Solar Professional
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#9d4300'
  on-secondary: '#ffffff'
  secondary-container: '#fd761a'
  on-secondary-container: '#5c2400'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002113'
  on-tertiary-container: '#009668'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  metric-xl:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
The design system is engineered to project stability, technological leadership, and the warmth of the Philippine sun. It balances the rigor of a high-end engineering firm with the accessibility of a modern SaaS platform. 

The aesthetic is **Corporate Modern**, characterized by generous whitespace, precision-aligned components, and a clear visual hierarchy. It avoids unnecessary decorative elements, focusing instead on data clarity and "savings" as the primary value proposition. The UI should feel reliable and high-fidelity, reassuring homeowners and commercial partners of the long-term viability of solar investment.

## Colors
This palette utilizes high-contrast pairings to drive action and convey authority. 

*   **Primary (Deep Navy):** Used for navigation, headers, and text to establish a foundation of trust and professional integrity.
*   **Accent (Solar Orange):** Reserved for primary calls to action (CTAs), interactive sliders, and urgency-based indicators. 
*   **Success (Emerald Green):** Specifically used for "Savings" metrics, ROI highlights, and environmental impact data.
*   **Neutral (Slate & White):** Used for background layering and subtle structural divisions to maintain a clean, airy feel.

## Typography
The typography strategy pairs the geometric strength of **Montserrat** for headings with the clinical legibility of **Inter** for UI and body text. 

Headlines should use tight letter-spacing to appear more impactful and "engineered." For financial data and savings calculations, use the **Metric-XL** style to ensure the ₱ symbol and numerical values are the most prominent elements on the page. All labels and overlines should use the uppercase **Label-MD** style to differentiate meta-information from primary content.

## Layout & Spacing
The design system employs a **12-column fixed grid** for desktop and a **fluid 4-column grid** for mobile. 

A strict 8px-based spatial system ensures consistency across all components. Spacing between major sections should be generous (80px–120px) to maintain a premium, uncluttered feel. Components like "Metric Cards" should use 24px internal padding (gutter-equivalent) to allow data breathing room. When displaying energy production charts or calculators, utilize "Safe Areas" with 32px padding to keep the technical data contained and readable.

## Elevation & Depth
Hierarchy is established through **Ambient Shadows** and **Tonal Layering**. 

The base background is the light gray neutral (#F8FAFC). Primary content areas use white (#FFFFFF) surfaces with extremely soft, large-radius shadows (Blur: 20px, Opacity: 4%, Color: Navy Blue). This creates a "floating" effect that mimics modern SaaS dashboard aesthetics. 

Metric cards and calculator containers use a slightly more pronounced elevation to indicate interactivity. Borders are rarely used; depth is instead conveyed through subtle value shifts between the background and surface layers.

## Shapes
The design system uses a consistent **2xl (1.5rem / 24px)** corner radius for all primary containers and cards to soften the industrial nature of solar technology. 

Interactive elements like buttons and input fields utilize a slightly tighter radius (0.75rem / 12px) to feel more precise. Sliders and toggle tracks are fully rounded (pill-shaped) to provide a friendly, tactile experience during the "Solar Calculator" flow.

## Components
*   **Metric Cards:** The centerpiece of the dashboard. These feature a large Emerald Green ₱ value, a Montserrat label, and a subtle sparkline chart showing energy production.
*   **Buttons:** Primary buttons are Solar Orange (#F97316) with bold white Inter text. They use a subtle inner glow on hover to feel tactile and "energized."
*   **Calculators:** Sliders use a thick Navy track with an oversized Solar Orange thumb for easy manipulation on mobile devices.
*   **Inputs:** Clean white fields with 1px Slate borders. Upon focus, the border transitions to Primary Navy with a soft shadow.
*   **Status Chips:** Small, semi-transparent pills (e.g., Emerald Green at 10% opacity for "Online" or "Saving") with high-contrast text.
*   **Lists:** Used for breakdown of installation steps or billing history. Items are separated by subtle gray dividers with 16px vertical padding.