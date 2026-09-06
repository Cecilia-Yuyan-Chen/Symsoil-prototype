---
name: 共壤 OS
colors:
  surface: '#fdf9f4'
  surface-dim: '#ddd9d5'
  surface-bright: '#fdf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ee'
  surface-container: '#f1ede8'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e6e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#504441'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0eb'
  outline: '#827470'
  outline-variant: '#d4c3be'
  surface-tint: '#77574d'
  primary: '#442a22'
  on-primary: '#ffffff'
  primary-container: '#5d4037'
  on-primary-container: '#d4ada1'
  inverse-primary: '#e7bdb1'
  secondary: '#3c6a00'
  on-secondary: '#ffffff'
  secondary-container: '#b8f47a'
  on-secondary-container: '#407100'
  tertiary: '#502400'
  on-tertiary: '#ffffff'
  tertiary-container: '#723600'
  on-tertiary-container: '#ff9d56'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#e7bdb1'
  on-primary-fixed: '#2c160e'
  on-primary-fixed-variant: '#5d4037'
  secondary-fixed: '#b8f47a'
  secondary-fixed-dim: '#9dd761'
  on-secondary-fixed: '#0e2000'
  on-secondary-fixed-variant: '#2c5000'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#ffb786'
  on-tertiary-fixed: '#311300'
  on-tertiary-fixed-variant: '#723600'
  background: '#fdf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e6e2dd'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter-sm: 12px
  gutter-md: 16px
  gutter-lg: 24px
  margin-screen: 20px
  radius-card: 16px
---

## Brand & Style

共壤 OS embodies a warm, natural rural aesthetic designed for community co-creation, agricultural collaboration, and rural revitalization. The design style blends Tactile and Modern principles—characterized by inviting textures, organic shapes, and generous whitespace. 

### Brand Personality & Audience
- **Personality:** Approachable, grounded, optimistic, and deeply connected to the earth and community.
- **Target Audience:** Rural entrepreneurs, agricultural workers, local artisans, community volunteers, and urban visitors seeking authentic rural experiences.
- **Emotional Response:** Evokes a sense of belonging, peace, reliability, and enthusiastic grassroots collaboration.

## Colors

The color palette grounds the digital experience in nature, drawing directly from fertile soil, fresh foliage, harvest citrus, and open skies.

- **Neutral (Background):** `#F9F5F0` (Rice White / Warm Cream) provides a soft, non-glare canvas that mimics natural unbleached paper or sun-baked plaster.
- **Primary (Earth Brown):** `#5D4037` anchors the UI with stability and heritage, used for primary typography, structural containers, and key interactive elements.
- **Secondary (Folio Green):** `#7CB342` represents sustainable growth, nature, and positive actions, ideal for success states, tags, and accent icons.
- **Tertiary (Youth Orange):** `#F57C00` injects vitality and warmth, reserved for calls-to-action, highlights, and community engagement prompts.
- **Operational Accent (Operation Blue):** `#1E88E5` serves as a functional contrast for informational badges, links, and system notifications without breaking the natural harmony.

## Typography

The typography pairing combines the friendly, rounded geometric forms of **Plus Jakarta Sans** for headlines with the warm, highly readable **Nunito Sans** for body and functional text. This combination bridges modern digital utility with a welcoming, human-centric tone.

## Layout & Spacing

The layout utilizes a fluid 12-column grid system paired with generous whitespace to create an unhurried, breathable reading and interaction experience. 

- **Grid & Margins:** On desktop, use a max-width container with 24px gutters and 32px side margins. On mobile devices, utilize a fluid 12-column layout with 20px edge margins (`margin-screen`) to ensure content never crowds the screen edge.
- **Rhythm:** Spacing increments follow an 8px base grid (8, 16, 24, 32, 48px), establishing consistent vertical rhythms between content blocks, cards, and section headers.

## Elevation & Depth

Visual hierarchy is communicated through soft, organic shadows and tonal layering rather than harsh borders or stark contrasts.

- **Ambient Shadows:** Shadows use diffused, warm-tinted spreads (using diluted Earth Brown `#5D4037` at 8-12% opacity) to mimic natural morning light falling across physical objects. 
- **Surface Tiers:** Cards and interactive containers sit on the base `#F9F5F0` background using pure white `#FFFFFF` or slightly tinted surfaces, creating gentle elevation steps that feel touchable and comforting.

## Shapes

The shape language relies heavily on friendly, rounded geometry (Option 2: Rounded). 

- **Border Radius:** Default UI elements feature a generous `16px` border radius (`rounded-md`), softening the interface to eliminate aggressive sharp corners. Major containers and cards utilize `24px` (`rounded-xl`), while small tags and interactive micro-elements scale down to `8px`.

## Components

- **Buttons:** Primary actions use Earth Brown (`#5D4037`) or Youth Orange (`#F57C00`) with a `16px` corner radius, subtle hover elevation, and clear `label-lg` typography. Secondary buttons use ghost outlines with primary text color.
- **Chips & Tags:** Pill-shaped (`rounded-full`) tags featuring soft secondary green (`#7CB342`) or operation blue (`#1E88E5`) backgrounds at low opacities for categorizing community topics and agricultural goods.
- **Input Fields:** Rounded (`16px`) input fields with rice white `#F9F5F0` or pure white backgrounds, subtle focus rings in Youth Orange (`#F57C00`), and comfortable internal padding for tactile ease of use.
- **Cards:** Elevated white cards set against the warm background, featuring `16px` to `24px` rounded corners, soft ambient shadows, and clear internal spacing for community stories, product listings, and event posts.
- **Checkboxes & Radio Buttons:** Custom styled with rounded corners and circles respectively, utilizing secondary green (`#7CB342`) for active states to reinforce natural feedback.
- **Lists:** Clean list rows separated by subtle tonal dividers, optimized for readability with generous tap targets (minimum 48px height) suited for outdoor and community mobile usage.