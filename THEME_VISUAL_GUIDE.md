# 🎨 Geta Theme Visual Guide

## Color Palette

```
┌─────────────────────────────────────────────┐
│  #FFD700 - GOLD (Primary Accent)           │
│  ████████████████████████████████████       │
│  Metallic gold for borders & highlights     │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  #B22222 - FIREBRICK RED (Backgrounds)      │
│  ████████████████████████████████████       │
│  Deep crimson for containers & overlays     │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  #B8860B - DARK GOLDENROD (Secondary)       │
│  ████████████████████████████████████       │
│  Darker gold for depth & variation          │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  #F5F5F5 - OFF-WHITE (Text)                 │
│  ████████████████████████████████████       │
│  Clean whitesmoke for readable text         │
└─────────────────────────────────────────────┘
```

---

## Typography Showcase

### Decorative Headers
**Font:** Cinzel Decorative
**Usage:** Main den title, special announcements
**Style:** UPPERCASE, ornate, commanding

### Section Headers  
**Font:** IM Fell English SC
**Usage:** Section titles, navigation
**Style:** Small caps, classic Roman

### Body Text
**Font:** Cinzel
**Usage:** General content, descriptions
**Style:** Clean, readable serif

### Gothic Accent
**Font:** UnifrakturMaguntia
**Usage:** Special decorative text
**Style:** Gothic blackletter (used sparingly)

---

## Layout Structure

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║         [MAIN HEADER WITH DECORATION]                     ║
║         alexisntfound's Den                               ║
║         ⚔️ Ave Caesar! Welcome to the Empire ⚔️          ║
║                                                           ║
╠═══════════════════════════════════════════════════════════╣
║                                                           ║
║  ┌─────────────────────────────────────────────────┐     ║
║  │  PRIDE OVERVIEW (Background Image)              │     ║
║  │  [Majestic lion scene with golden borders]     │     ║
║  │                                                 │     ║
║  │  Overlay box with pride description             │     ║
║  └─────────────────────────────────────────────────┘     ║
║                                                           ║
║  ┌─────────────────────────────────────────────────┐     ║
║  │  BASIC BOX (Rounded Corners)                    │     ║
║  │  ┌─ About This Pride ─────────────────────┐    │     ║
║  │  │ Golden border, firebrick background     │    │     ║
║  │  │ Rounded 15px, semi-transparent          │    │     ║
║  │  └─────────────────────────────────────────┘    │     ║
║  └─────────────────────────────────────────────────┘     ║
║                                                           ║
║  ─────────── [ROMAN DIVIDER] ──────────────              ║
║                                                           ║
║  ┌─────────────────────────────────────────────────┐     ║
║  │  QUEEN DYNASTY (Royal Background)               │     ║
║  │  👑 Queen Dynasty 👑                            │     ║
║  │  🦁 Queen Name 1 - Reign: ...                  │     ║
║  │  🦁 Queen Name 2 - Reign: ...                  │     ║
║  └─────────────────────────────────────────────────┘     ║
║                                                           ║
║  ┌─────────────────────────────────────────────────┐     ║
║  │  ALATUS BOX (Dramatic Background)               │     ║
║  │  [Large centered title with golden glow]       │     ║
║  │  Special Announcement                           │     ║
║  │  [Important content with shadow effects]       │     ║
║  └─────────────────────────────────────────────────┘     ║
║                                                           ║
║  ┌─────────────────────────────────────────────────┐     ║
║  │  FANCY COMMENT BOX                              │     ║
║  │  📝 Leave a Message                            │     ║
║  │  [Ornate background with golden border]        │     ║
║  │  [Text area with custom styling]               │     ║
║  │  [Golden submit button]                         │     ║
║  └─────────────────────────────────────────────────┘     ║
║                                                           ║
╠═══════════════════════════════════════════════════════════╣
║  CSS by pluto (#52831 / #58766) for alexisntfound       ║
║  Theme: Gladiator 2 / Geta / Roman Empire               ║
╚═══════════════════════════════════════════════════════════╝
```

---

## Visual Effects

### Golden Glow Effect
```
┌──────────────────┐
│   ✨ Content ✨  │  ← Subtle golden halo
│  [Glowing Box]   │     around element
└──────────────────┘
```

### Animated Pulse
```
┌──────────────────┐
│   Content Here   │  ← Glow pulses
│  [Pulsing Glow]  │     in/out smoothly
└──────────────────┘
```

### Rounded Borders
```
  ╭─────────────╮
  │   Content   │  ← All corners smoothly
  │   Rounded   │     rounded at 15px
  ╰─────────────╯
```

### Gothic Pixel Style
```
╔═══════════════╗
║  Pixelated    ║  ← Sharp edges mixed
║  Border Style ║     with smooth rounds
╚═══════════════╝
```

---

## Background Images

### Main Body Background
**Image:** Roman amphitheater/colosseum
**Effect:** Fixed, full cover, darkened
**Purpose:** Sets dramatic ancient Rome atmosphere

### Pride Overview
**Image:** Majestic lion in Roman setting
**Effect:** Center cover, overlay compatible
**Purpose:** Introduces pride with grandeur

### Dynasty Sections
**Image:** Royal imperial backgrounds
**Effect:** Cover, semi-transparent overlay
**Purpose:** Emphasizes lineage importance

### Special Boxes
**Image:** Ornate decorative patterns
**Effect:** Cover with content overlay
**Purpose:** Makes sections stand out

---

## Interactive Elements

### Buttons
```
┌─────────────────┐
│  SUBMIT BUTTON  │  ← Golden with dark border
└─────────────────┘
     ↓ Hover
┌─────────────────┐
│  SUBMIT BUTTON  │  ← Darkens, glows, lifts
└─────────────────┘
```

### Links
```
Regular: Gold (#FFD700)
Hover:   White with golden glow
Visited: Gold (consistent)
```

### Input Fields
```
┌───────────────────────────────┐
│ Text Input Field...           │  ← Dark gold background
└───────────────────────────────┘
     ↓ Focus
┌───────────────────────────────┐
│ Text Input Field...           │  ← Brighter, golden glow
└───────────────────────────────┘
```

---

## Spacing & Rhythm

### Section Spacing
- **Between major sections:** 20-30px
- **Inside containers:** 15-20px  
- **Text line height:** 1.6
- **Header margins:** 10-15px

### Border Specifications
- **Main containers:** 3px solid gold
- **Sub-sections:** 2px solid gold
- **Tables/cells:** 1-2px solid gold (50% opacity)
- **All rounded:** 10-15px radius

---

## Responsive Behavior

### Desktop (> 768px)
```
┌──────────────────────────────────────┐
│  Full Size                           │
│  - H1: 72px                          │
│  - H2: 36px                          │
│  - Containers: Max width respected   │
│  - Images: Full quality              │
└──────────────────────────────────────┘
```

### Mobile (< 768px)
```
┌────────────────┐
│  Scaled Down   │
│  - H1: 48px    │
│  - H2: 28px    │
│  - Responsive  │
│  - Touch OK    │
└────────────────┘
```

---

## Accessibility Features

✅ High contrast text (white on dark red)
✅ Readable font sizes (minimum 14px)
✅ Clear link colors (gold stands out)
✅ Touch-friendly buttons (8px+ padding)
✅ Text shadows for readability
✅ Semi-transparent overlays preserve images

---

## Gothic Pixel Aesthetic Elements

1. **Pixelated Image Rendering:** Sharp, crisp edges on graphics
2. **Layered Borders:** Multiple box shadows for depth
3. **Geometric Shapes:** Clean squares/rectangles with rounded corners
4. **Dark Atmosphere:** Rich reds and blacks
5. **Golden Accents:** Metallic highlights throughout
6. **Medieval Typography:** Gothic and Roman fonts
7. **Dramatic Lighting:** Glows and shadows

---

## Theme Mood Board

```
ANCIENT ROME          GLADIATOR 2           GOTHIC PIXEL
    ⚔️                   🏛️                    💀
  Colosseum            Geta Character        Dark Aesthetic
  Gold & Red           Imperial Power        Pixel Art
  Marble & Stone       Drama & Spectacle     Retro Digital

              ╲         │         ╱
               ╲        │        ╱
                ╲       │       ╱
                 ╲      │      ╱
                  ╲     │     ╱
                   ╲    │    ╱
                    ╲   │   ╱
                     ╲  │  ╱
                      ╲ │ ╱
                       ╲│╱
                        ▼
                 GETA THEME
           Powerful • Elegant • Dramatic
```

---

## Installation Preview

### Before (Default Lioden)
```
Plain white background
Standard blue links
Basic tables
No custom styling
Simple layout
```

### After (Geta Theme)
```
🏛️ Dramatic Roman amphitheater background
✨ Golden glowing links and borders
🎨 Richly styled containers with images
💫 Custom cursors and scrollbars
🎭 Professional, cohesive design
```

---

**This theme transforms your den into a Roman imperial palace!**

*Ave Caesar! Long live the Empire!* ⚔️🦁👑
