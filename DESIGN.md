---
name: Benevolent Harmony
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#454838'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#767966'
  outline-variant: '#c6c8b3'
  surface-tint: '#536600'
  primary: '#536600'
  on-primary: '#ffffff'
  primary-container: '#89a132'
  on-primary-container: '#293400'
  inverse-primary: '#b7d15d'
  secondary: '#5d5f5b'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0da'
  on-secondary-container: '#61635f'
  tertiary: '#635d58'
  on-tertiary: '#ffffff'
  tertiary-container: '#9d9690'
  on-tertiary-container: '#332f2a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3ee76'
  primary-fixed-dim: '#b7d15d'
  on-primary-fixed: '#171e00'
  on-primary-fixed-variant: '#3e4c00'
  secondary-fixed: '#e2e3dd'
  secondary-fixed-dim: '#c6c7c1'
  on-secondary-fixed: '#1a1c19'
  on-secondary-fixed-variant: '#454743'
  tertiary-fixed: '#eae1da'
  tertiary-fixed-dim: '#cdc5be'
  on-tertiary-fixed: '#1f1b17'
  on-tertiary-fixed-variant: '#4b4641'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 20px
  section-gap-lg: 120px
  section-gap-md: 80px
---

## Brand & Style

The design system is crafted to resonate with the philanthropic values of modern Korean women aged 30-50. It balances **warmth** and **premium professionalism**, moving away from clinical NGO aesthetics toward a more "lifestyle-integrated" charitable experience.

The style is a blend of **Soft Minimalism** and **Tactile Modernism**. It prioritizes high-clarity information architecture and generous whitespace to ensure the content—real stories of impact—takes center stage. The emotional goal is to evoke a sense of serene confidence, reassuring the donor that their contribution is handled with utmost care and sophistication.

Visual pillars include:
- **Abundant Negative Space:** To create a "breathable" and high-end editorial feel.
- **Organic Fluidity:** Utilizing soft, oversized radii to mimic natural forms and human touch.
- **Visual Honesty:** High-quality imagery combined with clean, unadorned layout structures.

## Typography

This design system utilizes a high-contrast typographic hierarchy to ensure accessibility and professional polish. While **Plus Jakarta Sans** provides a friendly, modern geometry for headlines, **Hanken Grotesk** (a high-quality alternative to Pretendard) offers exceptional legibility for body copy and data.

For the Korean implementation, use a sans-serif with a variable weight axis (like Pretendard JP/KR) to match these proportions. 
- **Headlines:** Should be bold and tightly spaced to feel impactful and confident.
- **Body Text:** Set with generous line height (1.6x) to accommodate the reading preferences of the 30-50 demographic.
- **Numeric Data:** Use the Hanken Grotesk medium/bold weights for impact figures (e.g., "88% success rate").

## Layout & Spacing

The layout philosophy follows an Adaptive-Fixed Hybrid. The page is designed for a 1920px canvas, and content is contained within a 1440px central spine for desktop viewing.

- **Vertical Rhythm:** A strict 8px baseline grid is used. However, section-to-section spacing is intentionally "oversized" (80px - 120px) to signify a premium, unhurried user journey.
- **Dynamic Padding:** Components like cards use inner padding of 32px or 40px to prevent a "cluttered" look.
- **Grid:** On desktop, a 12-column grid with 24px gutters. On mobile, a 4-column grid with 20px margins. Elements often "break the grid" slightly with organic offsets to create a dynamic, modern NGO aesthetic.

## Elevation & Depth

To maintain a "Warm & Trustworthy" feel, this design system avoids harsh, technical shadows. Instead, it uses **Tonal Layering** and **Soft Ambient Occlusion**.

- **Surface Tiers:** Depth is primarily communicated through color shifts (e.g., a white card on a `#F7F8F2` background) rather than heavy shadows.
- **Shadow Profile:** When elevation is necessary (e.g., for floating "Donate" buttons or active cards), use a very diffused, low-opacity shadow: `0 20px 40px rgba(74, 69, 64, 0.08)`. The shadow color is tinted with the Tertiary Umber rather than pure black to keep it "warm."
- **Glassmorphism:** Use sparingly for navigation overlays or image captions to provide a "frosted" premium feel without cluttering the interface.

## Shapes

The shape language is the core of this system's personality. It is **Decidedly Rounded**, evoking friendliness, safety, and care.

- **Small Components (Buttons, Inputs):** 16px radius.
- **Large Components (Cards, Image Containers):** 24px to 32px radius.
- **Extreme Rounding:** Pill shapes are used for badges, chips, and secondary buttons to contrast against the structural containers.
- **Image Treatment:** Photos should always follow the container's corner radius (24px+). For a premium feel, use "Squircle" (superellipse) masks where possible.

## Components

- **Buttons:** Primary buttons use the `#89A132` background with white text and 16px corner radius. They should have a minimum height of 56px for a tactile, premium feel. Secondary buttons use a thick outline or a light green tint.
- **Cards:** White backgrounds on off-white surfaces. Use 32px inner padding. Headers within cards should be bold and clearly separated from body content.
- **Input Fields:** Soft grey backgrounds (`#F1F2EB`) with 16px rounded corners. Focus states should use a 2px border of the Primary Green.
- **Progress Bars:** For fundraising goals, use a thick (12px) pill-shaped bar. The "filled" portion should be Primary Green, and the background should be a very light tint of the same color.
- **Impact Badges:** Small pill-shaped containers with low-contrast backgrounds and bold `label-sm` typography to highlight key stats or categories.
- **Navigation:** A clean, sticky top bar with plenty of height (80px+) and a clear, high-contrast "Donate" button at the far right.