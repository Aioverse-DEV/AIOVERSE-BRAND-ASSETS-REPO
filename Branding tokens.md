# # Aiotize Inc. Brand Guidelines

## Version 1.0 | 2025

-----

## 1. Brand Identity

### 1.1 Brand Essence

**Vision**: Pioneering the future of AI-driven solutions
**Mission**: Transforming businesses through intelligent automation
**Values**: Innovation, Precision, Accessibility, Trust

### 1.2 Brand Voice

- **Professional** yet approachable
- **Technical** but clear
- **Forward-thinking** and innovative
- **Confident** without being arrogant

-----

## 2. Logo System

### 2.1 Primary Logo Variants

#### Logomark

- **File**: `AIOTIZE_Logomark_Black.svg`
- **Usage**: Icon, app symbol, favicon
- **Minimum Size**: 24px × 24px
- **Clear Space**: 0.5× logo height on all sides

#### Wordmark

- **File**: `AIOTIZE_Wordmark_Black.svg`
- **Usage**: Primary brand identifier
- **Minimum Size**: 120px width
- **Clear Space**: 1× cap height on all sides

#### Combination Mark

- **File**: `AIOTIZE_Logo_Full_Black.svg`
- **Usage**: Default logo for most applications
- **Minimum Size**: 180px width
- **Clear Space**: 1× logomark height on all sides

### 2.2 Logo Variants

```
Primary Variants:
├── AIOTIZE_Logo_Gradient_Primary.svg
├── AIOTIZE_Logo_Black.svg
├── AIOTIZE_Logo_White.svg
├── AIOTIZE_Logo_Monochrome.svg
└── AIOTIZE_Logo_Knockout.svg

Contextual Variants:
├── AIOTIZE_Logo_Dark_Mode.svg
├── AIOTIZE_Logo_Light_Mode.svg
└── AIOTIZE_Logo_High_Contrast.svg
```

### 2.3 Logo Grid & Construction

- **Grid System**: 8×8 modular grid
- **Aspect Ratio**: 3:1 (combination mark)
- **Optical Balance**: 60% logomark, 40% wordmark
- **Baseline Alignment**: Wordmark sits on 2nd grid line from bottom

-----

## 3. Color System

### 3.1 Primary Palette

```css
/* Core Brand Colors */
--aiotize-black: #0A0A0B;
--aiotize-white: #FFFFFF;
--aiotize-gradient-start: #6366F1;  /* Indigo */
--aiotize-gradient-end: #EC4899;    /* Pink */
```

### 3.2 Extended Palette

```css
/* Neutral Scale */
--neutral-950: #0A0A0B;
--neutral-900: #171717;
--neutral-800: #262626;
--neutral-700: #404040;
--neutral-600: #525252;
--neutral-500: #737373;
--neutral-400: #A3A3A3;
--neutral-300: #D4D4D4;
--neutral-200: #E5E5E5;
--neutral-100: #F5F5F5;
--neutral-50:  #FAFAFA;

/* Accent Colors */
--accent-purple: #8B5CF6;
--accent-blue: #3B82F6;
--accent-cyan: #06B6D4;
--accent-emerald: #10B981;
--accent-amber: #F59E0B;
--accent-rose: #F43F5E;
```

### 3.3 Semantic Colors

```css
/* Functional Colors */
--success: #10B981;
--warning: #F59E0B;
--error: #EF4444;
--info: #3B82F6;

/* Surface Colors */
--surface-primary: var(--neutral-950);
--surface-secondary: var(--neutral-900);
--surface-tertiary: var(--neutral-800);
--surface-overlay: rgba(10, 10, 11, 0.8);
```

### 3.4 Gradient System

```css
/* Primary Gradient */
--gradient-primary: linear-gradient(135deg, #6366F1 0%, #EC4899 100%);

/* Secondary Gradients */
--gradient-cool: linear-gradient(135deg, #3B82F6 0%, #06B6D4 100%);
--gradient-warm: linear-gradient(135deg, #F59E0B 0%, #F43F5E 100%);
--gradient-neural: linear-gradient(135deg, #8B5CF6 0%, #6366F1 100%);

/* Mesh Gradients */
--gradient-mesh: radial-gradient(at 40% 20%, #6366F1 0%, transparent 50%),
                 radial-gradient(at 80% 0%, #EC4899 0%, transparent 50%),
                 radial-gradient(at 10% 50%, #8B5CF6 0%, transparent 50%);
```

-----

## 4. Typography

### 4.1 Font Stack

```css
/* Display Font - Headlines & Hero Text */
@font-face {
  font-family: 'Aiotize Display';
  src: url('fonts/GeistMono-Black.woff2') format('woff2');
  font-weight: 900;
}

/* Logo Font - Brand Wordmark */
@font-face {
  font-family: 'Aiotize Brand';
  src: url('fonts/GeistMono-Bold.woff2') format('woff2');
  font-weight: 700;
}

/* Header Font - Section Headers */
@font-face {
  font-family: 'Aiotize Sans';
  src: url('fonts/Geist-SemiBold.woff2') format('woff2');
  font-weight: 600;
}

/* Body Font - Content */
@font-face {
  font-family: 'Aiotize Text';
  src: url('fonts/Geist-Regular.woff2') format('woff2');
  font-weight: 400;
}

/* Code Font - Technical Content */
@font-face {
  font-family: 'Aiotize Mono';
  src: url('fonts/GeistMono-Regular.woff2') format('woff2');
  font-weight: 400;
}
```

### 4.2 Type Scale

```css
/* Fluid Type Scale */
--text-xs: clamp(0.75rem, 0.7rem + 0.25vw, 0.875rem);
--text-sm: clamp(0.875rem, 0.8rem + 0.375vw, 1rem);
--text-base: clamp(1rem, 0.9rem + 0.5vw, 1.125rem);
--text-lg: clamp(1.125rem, 1rem + 0.625vw, 1.25rem);
--text-xl: clamp(1.25rem, 1.1rem + 0.75vw, 1.5rem);
--text-2xl: clamp(1.5rem, 1.3rem + 1vw, 1.875rem);
--text-3xl: clamp(1.875rem, 1.6rem + 1.375vw, 2.25rem);
--text-4xl: clamp(2.25rem, 1.9rem + 1.75vw, 3rem);
--text-5xl: clamp(3rem, 2.5rem + 2.5vw, 3.75rem);
--text-6xl: clamp(3.75rem, 3rem + 3.75vw, 4.5rem);
```

### 4.3 Typography Tokens

```css
/* Line Heights */
--leading-none: 1;
--leading-tight: 1.25;
--leading-snug: 1.375;
--leading-normal: 1.5;
--leading-relaxed: 1.625;
--leading-loose: 2;

/* Letter Spacing */
--tracking-tighter: -0.05em;
--tracking-tight: -0.025em;
--tracking-normal: 0;
--tracking-wide: 0.025em;
--tracking-wider: 0.05em;
--tracking-widest: 0.1em;

/* Font Weights */
--font-thin: 100;
--font-light: 300;
--font-normal: 400;
--font-medium: 500;
--font-semibold: 600;
--font-bold: 700;
--font-black: 900;
```

-----

## 5. Spacing & Layout

### 5.1 Spacing Scale

```css
/* Base: 4px */
--space-0: 0;
--space-1: 0.25rem;  /* 4px */
--space-2: 0.5rem;   /* 8px */
--space-3: 0.75rem;  /* 12px */
--space-4: 1rem;     /* 16px */
--space-5: 1.25rem;  /* 20px */
--space-6: 1.5rem;   /* 24px */
--space-8: 2rem;     /* 32px */
--space-10: 2.5rem;  /* 40px */
--space-12: 3rem;    /* 48px */
--space-16: 4rem;    /* 64px */
--space-20: 5rem;    /* 80px */
--space-24: 6rem;    /* 96px */
--space-32: 8rem;    /* 128px */
```

### 5.2 Container Widths

```css
--container-xs: 20rem;    /* 320px */
--container-sm: 24rem;    /* 384px */
--container-md: 28rem;    /* 448px */
--container-lg: 32rem;    /* 512px */
--container-xl: 36rem;    /* 576px */
--container-2xl: 42rem;   /* 672px */
--container-3xl: 48rem;   /* 768px */
--container-4xl: 56rem;   /* 896px */
--container-5xl: 64rem;   /* 1024px */
--container-6xl: 72rem;   /* 1152px */
--container-7xl: 80rem;   /* 1280px */
--container-full: 100%;
```

-----

## 6. Component Tokens

### 6.1 Border Radius

```css
--radius-none: 0;
--radius-sm: 0.125rem;
--radius-base: 0.25rem;
--radius-md: 0.375rem;
--radius-lg: 0.5rem;
--radius-xl: 0.75rem;
--radius-2xl: 1rem;
--radius-3xl: 1.5rem;
--radius-full: 9999px;
```

### 6.2 Shadows

```css
--shadow-sm: 0 1px 2px 0 rgb(0 0 0 / 0.05);
--shadow-base: 0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);
--shadow-md: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
--shadow-lg: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
--shadow-xl: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
--shadow-2xl: 0 25px 50px -12px rgb(0 0 0 / 0.25);
--shadow-inner: inset 0 2px 4px 0 rgb(0 0 0 / 0.05);
--shadow-glow: 0 0 20px rgb(99 102 241 / 0.2);
```

### 6.3 Animation Tokens

```css
/* Durations */
--duration-75: 75ms;
--duration-100: 100ms;
--duration-150: 150ms;
--duration-200: 200ms;
--duration-300: 300ms;
--duration-500: 500ms;
--duration-700: 700ms;
--duration-1000: 1000ms;

/* Easings */
--ease-in: cubic-bezier(0.4, 0, 1, 1);
--ease-out: cubic-bezier(0, 0, 0.2, 1);
--ease-in-out: cubic-bezier(0.4, 0, 0.2, 1);
--ease-spring: cubic-bezier(0.5, 1.25, 0.75, 1.25);
```

-----

## 7. Graphic Templates

### 7.1 Template Structure

```
Templates/
├── Social/
│   ├── Twitter_Post_1200x675.svg
│   ├── LinkedIn_Post_1200x627.svg
│   └── Instagram_Post_1080x1080.svg
├── Presentation/
│   ├── Slide_16x9.svg
│   ├── Slide_4x3.svg
│   └── Slide_Cover.svg
├── Web/
│   ├── Hero_Banner_1920x600.svg
│   ├── Feature_Card_400x300.svg
│   └── CTA_Banner_1200x200.svg
└── Print/
    ├── Business_Card_3.5x2.svg
    ├── Letterhead_A4.svg
    └── Envelope_DL.svg
```

### 7.2 Graphic Framework

- **Grid**: 12-column with 24px gutters
- **Overlay Style**: Glassmorphism with blur backdrop
- **Gradient Application**: 45° angle for consistency
- **Typography Hierarchy**: Display → Header → Body
- **Icon Style**: 2px stroke, rounded caps
- **Image Treatment**: Duotone with brand gradient

-----

## 8. Digital Asset Library

### 8.1 File Naming Convention

```
[BRAND]_[TYPE]_[VARIANT]_[SIZE].[FORMAT]

Examples:
AIOTIZE_Logo_Primary_1024.png
AIOTIZE_Icon_App_512.svg
AIOTIZE_Pattern_Mesh_01.svg
AIOTIZE_Illustration_Hero_01.png
```

### 8.2 Asset Organization

```
Aiotize_Brand_Assets/
├── 01_Logo/
│   ├── SVG/
│   ├── PNG/
│   ├── PDF/
│   └── Source/
├── 02_Typography/
│   ├── Fonts/
│   └── Specimens/
├── 03_Colors/
│   ├── Swatches/
│   └── Palettes/
├── 04_Icons/
│   ├── System/
│   └── Custom/
├── 05_Patterns/
│   ├── Geometric/
│   └── Organic/
├── 06_Templates/
│   ├── Digital/
│   └── Print/
└── 07_Guidelines/
    ├── PDF/
    └── Markdown/
```

-----

## 9. Implementation Guidelines

### 9.1 Web Usage

```html
<!-- Logo Implementation -->
<picture>
  <source media="(prefers-color-scheme: dark)" 
          srcset="assets/AIOTIZE_Logo_White.svg">
  <source media="(prefers-color-scheme: light)" 
          srcset="assets/AIOTIZE_Logo_Black.svg">
  <img src="assets/AIOTIZE_Logo_Black.svg" 
       alt="Aiotize Inc." 
       width="180" 
       height="60">
</picture>
```

### 9.2 CSS Variables Implementation

```css
:root {
  /* Import all tokens */
  @import 'tokens/colors.css';
  @import 'tokens/typography.css';
  @import 'tokens/spacing.css';
  @import 'tokens/components.css';
}

.aiotize-theme-dark {
  --bg-primary: var(--neutral-950);
  --text-primary: var(--neutral-50);
}

.aiotize-theme-light {
  --bg-primary: var(--neutral-50);
  --text-primary: var(--neutral-950);
}
```

### 9.3 Accessibility Standards

- **Color Contrast**: WCAG AAA compliance (7:1 ratio)
- **Focus States**: Visible outline with 3px offset
- **Touch Targets**: Minimum 44×44px
- **Alt Text**: Descriptive for all visual elements
- **Semantic HTML**: Proper heading hierarchy
- **ARIA Labels**: For interactive elements

-----

## 10. Usage Examples

### 10.1 Do’s ✓

- Use gradient on dark backgrounds
- Maintain clear space around logo
- Use approved color combinations
- Follow type hierarchy
- Apply consistent spacing

### 10.2 Don’ts ✗

- Don’t distort logo proportions
- Don’t use unapproved colors
- Don’t place logo on busy backgrounds
- Don’t modify typography weights
- Don’t create custom gradients

-----

## Appendix

### Version History

- v1.0 - Initial release (2025)

### Contact

**Brand Team**: brand@aiotize.com
**Design System**: design@aiotize.com

### Resources

- [Brand Portal](https://brand.aiotize.com)
- [Asset Library](https://assets.aiotize.com)
- [Developer Docs](https://docs.aiotize.com/brand)

-----

© 2025 Aiotize Inc. All rights reserved.



[!DOCTYPE html.md](!DOCTYPE%20html.md)<!-- {"embed":"true"} -->