---
name: Elite Estate Framework
colors:
  surface: '#faf9fc'
  surface-dim: '#dbd9dd'
  surface-bright: '#faf9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f6'
  surface-container: '#efedf0'
  surface-container-high: '#e9e7eb'
  surface-container-highest: '#e3e2e5'
  on-surface: '#1b1b1e'
  on-surface-variant: '#44474e'
  inverse-surface: '#303033'
  inverse-on-surface: '#f2f0f3'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#495f82'
  primary: '#001026'
  on-primary: '#ffffff'
  primary-container: '#0b2545'
  on-primary-container: '#778db2'
  inverse-primary: '#b1c7f0'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#101010'
  on-tertiary: '#ffffff'
  tertiary-container: '#252525'
  on-tertiary-container: '#8d8c8c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#b1c7f0'
  on-primary-fixed: '#001c3b'
  on-primary-fixed-variant: '#314769'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#faf9fc'
  on-background: '#1b1b1e'
  surface-variant: '#e3e2e5'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system embodies the "Glory of Trust," catering to high-net-worth individuals and corporate entities seeking premium real estate solutions. The brand personality is authoritative yet welcoming, reflecting a legacy of architectural excellence and unwavering reliability.

The visual style is **Corporate / Modern** with a lean toward **Minimalism**. It prioritizes clarity and high-end aesthetics through significant whitespace, a disciplined color palette, and structured layouts. The goal is to evoke a sense of permanence and "Elite" status, mimicking the sophisticated presence of market leaders like Nyati Group. All visual elements are designed to feel intentional, professional, and trustworthy.

## Colors

The palette is anchored by **Deep Corporate Blue**, conveying stability and professional depth. **Rich Gold** is used as a strategic accent to denote premium quality, luxury, and success, primarily for call-to-actions and highlights.

**Slate Gray** serves as the primary text color to maintain high legibility without the harshness of pure black, while **White** provides a clean, expansive canvas that allows architectural photography to stand out. Secondary neutrals like light gray (#F5F5F5) may be used for subtle background sections to create soft tonal shifts.

## Typography

The typography strategy pairs the geometric strength of **Montserrat** for headings with the systematic clarity of **Inter** for body text. 

Headings should use tight tracking and bold weights to command attention, reflecting the "Heights" and "Residency" naming conventions of the properties. Body text is optimized for readability with generous line heights. Labels and small navigation elements use all-caps Inter with increased letter spacing to create a sophisticated, "architectural" feel.

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop to maintain a controlled, premium editorial feel, transitioning to a fluid model for smaller devices. 

- **Desktop:** 12-column grid with a 1200px max-width. Use 24px gutters.
- **Tablet:** 8-column grid with 24px gutters and 32px side margins.
- **Mobile:** 4-column fluid grid with 16px side margins.

Spacing follows an 8px base unit. Property listings and project galleries should utilize asymmetrical layouts occasionally to feel like a high-end brochure, but functional forms and data-heavy tables must remain strictly aligned to the grid.

## Elevation & Depth

To maintain a clean and elite appearance, this system avoids heavy drop shadows. Instead, depth is communicated through:

1.  **Tonal Layers:** Using extremely subtle light gray (#F8F9FA) backgrounds to separate content sections.
2.  **Low-Contrast Outlines:** Cards and input fields use a 1px solid border in a soft silver-gray (#E0E0E0) rather than shadows.
3.  **Strategic Gold Accents:** Gold is used on the "top" layer for active states or primary buttons, creating a mental model of importance through color rather than physical height.
4.  **Sharp Image Masking:** High-resolution architectural photography is treated as the primary "depth" element, often spanning the full width or breaking the grid.

## Shapes

The shape language is **Soft (0.25rem)**. While the properties are tall and structured, the digital interface uses slight rounding to appear modern and accessible. 

Primary buttons and property image cards use `rounded-sm`. Interactive elements like search bars or input fields follow this same subtle radius. Circular elements are reserved strictly for the corporate logo or small status indicators (like "Available" dots) to maintain the overall rectangular, structured professional aesthetic.

## Components

### Buttons
- **Primary:** Deep Corporate Blue background, white text, 0.25rem radius.
- **Secondary/Accent:** Rich Gold background, Deep Blue text for high contrast. Used for "Book Now" or "Inquiry."
- **Ghost:** 1px Deep Blue border with Deep Blue text.

### Cards
Property cards should feature a large image header, a Rich Gold "Status" chip (e.g., "Completed"), and a structured footer containing the property name in Montserrat and price/location in Inter. Borders are 1px soft gray.

### Input Fields
Clean, minimalist design with a 1px gray border that shifts to Deep Blue on focus. Labels sit above the field in uppercase Inter (Label-md).

### Progress Indicators
For "Completed Projects," use a Rich Gold progress bar or badge to celebrate the milestone.

### Navigation
Top-bar navigation is sticky with a white background and a subtle bottom border. High-level menu items use Montserrat Bold in small sizes with wide tracking.