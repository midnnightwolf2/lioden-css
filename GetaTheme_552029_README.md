# Geta Theme - Lioden Den CSS
## For alexisntfound (#552029)

**Created by:** pluto (#52831 / #58766)  
**Theme:** Gladiator 2 / Geta / Roman Empire / Gothic Pixel  
**Package:** Platinum (25 GB)

---

## 🎨 Color Scheme

- **#F5F5F5** - Off-white/Whitesmoke (main text)
- **#FFD700** - Gold (borders, accents, links)
- **#B22222** - Firebrick Red (backgrounds, overlays)
- **#B8860B** - Dark Goldenrod (secondary accents)

---

## 📋 Installation Instructions

### Step 1: Install the CSS
1. Go to your den page on Lioden
2. Click "Edit Den" or access your den settings
3. Find the CSS section
4. Copy the entire contents of `GetaTheme_552029.css`
5. Paste it into your den's CSS box
6. Save changes

### Step 2: Add HTML Content
1. Copy sections from `GetaTheme_552029_html.txt` that you want to use
2. Paste them into your den's HTML editor
3. Customize the text and content to fit your pride
4. Save changes

---

## 🎭 Features Included

### ✅ Core Styling
- [x] Custom Roman/Gothic fonts (Cinzel, IM Fell English SC, UnifrakturMaguntia)
- [x] Main background image
- [x] Custom cursor
- [x] Scrollbar styling
- [x] Rounded borders throughout
- [x] Golden glow effects

### ✅ Special Sections
- [x] **Main Header Decoration** - Behind your den name
- [x] **Pride Overview** - With custom background
- [x] **Pregnant Lionesses** - Special section with image
- [x] **Other Dens** - 4 different image backgrounds for branch dens
- [x] **Dynasty Lists** - General, Queen, and Pride dynasties
- [x] **Achievements** - With image header
- [x] **Showcase** - Display special items/lions
- [x] **Beetle Book** - Beetle collection section
- [x] **Mound Section** - For mound information

### ✅ Add-Ons
- [x] **Lioness Cave Background** - Animated GIF background for cave sections
- [x] **Image Headers** - For sections like achievements, bookmarks
- [x] **Basic Boxes** - Reusable content containers
- [x] **Fancy Comment Box** - Stylized guestbook/comment area
- [x] **Alatus Box** - Special announcement box with dramatic styling
- [x] **Roman Dividers** - Decorative section breaks

---

## 🎨 CSS Classes Reference

### Content Boxes
```html
<div class="basic-box">Your content here</div>
```
- General-purpose content container with Roman theme styling

### Image Sections
```html
<div class="pride-overview">Pride info</div>
<div class="pregnant-lionesses">Expecting mothers</div>
<div class="achievements">Your achievements</div>
<div class="showcase">Featured items</div>
<div class="beetle-book">Beetle collection</div>
```

### Dynasty Sections
```html
<div class="dynasty-list">General dynasty</div>
<div class="queen-dynasty">Queen lineage</div>
<div class="pride-dynasty">King lineage</div>
```

### Other Dens
```html
<div class="other-dens">
  <div class="other-dens-image-1">Branch 1</div>
  <div class="other-dens-image-2">Branch 2</div>
  <div class="other-dens-image-3">Branch 3</div>
  <div class="other-dens-image-4">Branch 4</div>
</div>
```

### Special Boxes
```html
<div class="comment-box">Comment/guestbook area</div>
<div class="alatus-box">Important announcements</div>
<div class="lioness-cave">Lioness territory</div>
```

### Decorative Elements
```html
<div class="roman-divider"></div>  <!-- Section divider -->
<div class="image-header">Section Title</div>  <!-- Image-based header -->
```

### Special Effects
Add these classes to any element for extra styling:
```html
<div class="basic-box pixel-border">Gothic pixel borders</div>
<div class="basic-box glow-gold">Golden glow effect</div>
<div class="basic-box animated-glow">Pulsing glow animation</div>
```

---

## 🖼️ Image Sources

All images used in this theme:

- **Background:** Roman amphitheater/colosseum scene
- **Main Header Decoration:** Gladiator-themed decorative element
- **Pregnant Lionesses:** Elegant lioness portrait
- **Pride Overview:** Majestic lion in Roman setting
- **Other Dens (4 images):** Various Roman/gladiator themed images
- **Dynasty Lists:** Royal/imperial themed backgrounds
- **Queen Dynasty:** Regal female-focused imagery
- **Pride Dynasty:** Powerful male-focused imagery
- **Achievements:** Victory/triumph themed
- **Showcase:** Spotlight/display themed
- **Beetle Book:** Ancient tome aesthetic
- **Fancy Comment Box:** Ornate decorative background
- **Alatus Box:** Dramatic announcement background
- **Image Headers:** Roman column/architecture element
- **Lioness Cave:** Animated pixel art cave scene

---

## 🎯 Customization Tips

### Changing Colors
To modify colors, edit the CSS variables in the `:root` section:
```css
:root {
  --whitesmoke: 245, 245, 245;
  --gold: 255, 215, 0;
  --firebrick: 178, 34, 34;
  --darkgold: 184, 134, 11;
}
```

### Adjusting Transparency
Modify opacity values:
```css
:root {
  --opacity-high: 0.95;  /* Nearly opaque */
  --opacity-med: 0.75;   /* Medium */
  --opacity-low: 0.5;    /* More transparent */
}
```

### Swapping Images
Find the image URL in the CSS and replace it:
```css
.pride-overview {
  background: url('YOUR-NEW-IMAGE-URL') center center no-repeat;
}
```

### Border Radius
All rounded corners use `border-radius`. Search for `border-radius: 15px;` and adjust the value for more or less rounding.

---

## 📱 Responsive Design

The theme includes mobile-friendly adjustments:
- Headers scale down on smaller screens
- Containers remain readable
- Touch-friendly button sizes

---

## ⚠️ Important Notes

1. **Copyright:** This theme is for your personal use only. Do not share or redistribute the code.
2. **Credits:** Please keep the credit line intact in the CSS.
3. **Editing:** You may edit the theme, but keep attribution to the original creator.
4. **Support:** Contact pluto (#52831 / #58766) on Lioden for questions or issues.

---

## 🎨 Gothic Pixel Aesthetic

This theme combines:
- **Roman Empire** grandeur and architecture
- **Gladiator 2 / Geta** character inspiration
- **Gothic** dark, dramatic styling
- **Pixel Art** retro gaming aesthetic with modern CSS

The result is a unique blend of ancient imperial majesty and modern digital art.

---

## 🆘 Troubleshooting

### CSS Not Showing
- Make sure you copied the ENTIRE CSS file
- Check that you saved changes after pasting
- Clear your browser cache and refresh

### Images Not Loading
- Check your internet connection
- Some image hosts may be slow
- Images are hosted externally and should work

### Layout Issues
- Make sure HTML is properly closed (all `<div>` tags have matching `</div>`)
- Check for typos in class names
- Validate HTML structure

### Colors Look Wrong
- Check monitor color calibration
- Different browsers may render colors slightly differently
- Ensure you're viewing in a well-lit environment

---

## 📞 Contact

For questions, issues, or custom modifications:
- **Lioden:** pluto (#52831 / #58766)
- **Commissioner:** alexisntfound (#552029)

---

**Thank you for choosing this custom theme!**

*Ave Caesar! Long live the Empire!* ⚔️🦁👑
