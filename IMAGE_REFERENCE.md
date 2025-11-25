# 📸 Image Reference Guide - Geta Theme

## All Images Applied and Integrated

This document shows where each requested image is used in the CSS theme.

---

## 🖼️ Image Locations in CSS

### 1. Background Image
**URL:** `https://i.pinimg.com/736x/bd/80/b3/bd80b38dafac58c68dfc7255a1b706b8.jpg`  
**Location:** Line 103 in CSS  
**Applied to:** `body` element (main page background)  
**Effect:** Fixed, full-cover Roman amphitheater scene

```css
body {
  background: url('https://i.pinimg.com/736x/bd/80/b3/bd80b38dafac58c68dfc7255a1b706b8.jpg') 
              center center fixed no-repeat;
  background-size: cover;
}
```

---

### 2. Unsorted (Lioness Cave Animated GIF)
**URL:** `https://i.ibb.co/DDNkp0c0/tumblr-cadb016ab0f74ce7e9da3480925651f0-62e90ed3-400.gif`  
**Location:** Line 656 in CSS  
**Applied to:** `.cave-container`, `.lioness-cave` classes  
**Effect:** Animated cave background with gradient overlay

```css
.cave-container, .lioness-cave {
  background: linear-gradient(rgba(var(--firebrick), 0.5), rgba(var(--darkgold), 0.3)),
              url('https://i.ibb.co/DDNkp0c0/tumblr-cadb016ab0f74ce7e9da3480925651f0-62e90ed3-400.gif') 
              center center no-repeat;
}
```

---

### 3. Pregnant Lionesses
**URL:** `https://i.pinimg.com/736x/9d/b7/3d/9db73dec4edf4c5d26150216f4bea61c.jpg`  
**Location:** Line 413 in CSS  
**Applied to:** `.pregnant-lionesses` class  
**Effect:** Background image for pregnant lionesses section

```css
.pregnant-lionesses {
  background: url('https://i.pinimg.com/736x/9d/b7/3d/9db73dec4edf4c5d26150216f4bea61c.jpg') 
              center center no-repeat;
  background-size: cover;
}
```

---

### 4. Pride Overview
**URL:** `https://i.pinimg.com/736x/1b/bb/a4/1bbba484d906a2bfda0089a054420ca7.jpg`  
**Location:** Lines 424 & 700 in CSS  
**Applied to:** 
- `.pride-overview` class (line 424)
- `.featured-lion` class (line 700) - for cave page featured lion

```css
/* Pride Overview Section */
.pride-overview {
  background: url('https://i.pinimg.com/736x/1b/bb/a4/1bbba484d906a2bfda0089a054420ca7.jpg') 
              center center no-repeat;
}

/* Featured Lion on Cave Page */
.featured-lion {
  background: linear-gradient(rgba(var(--firebrick), 0.6), rgba(var(--darkgold), 0.4)),
              url('https://i.pinimg.com/736x/1b/bb/a4/1bbba484d906a2bfda0089a054420ca7.jpg') 
              center center no-repeat;
}
```

---

### 5. Other Dens Images (4 Images)

#### Image 1
**URL:** `https://i.ibb.co/whGYb70Y/tumblr-c0c84d2edf4ef65bf7ab7ec6d6ff105b-3b8c59f6-400.webp`  
**Location:** Line 444 in CSS  
**Applied to:** `.other-dens-image-1` class

#### Image 2
**URL:** `https://i.ibb.co/7JK3K3zg/tumblr-80bf543a59fab434794cbd3d6beb4050-1b91f5f7-400.webp`  
**Location:** Line 452 in CSS  
**Applied to:** `.other-dens-image-2` class

#### Image 3
**URL:** `https://i.pinimg.com/736x/46/ea/4d/46ea4db2021a7e3decc98f8a7a63adf3.jpg`  
**Location:** Line 460 in CSS  
**Applied to:** `.other-dens-image-3` class

#### Image 4
**URL:** `https://i.pinimg.com/736x/54/ac/5f/54ac5f61eab2824f12f49c9f8b8a3c53.jpg`  
**Location:** Line 468 in CSS  
**Applied to:** `.other-dens-image-4` class

```css
.other-dens-image-1 {
  background: url('https://i.ibb.co/whGYb70Y/...') center center no-repeat;
}
/* Similar for images 2, 3, and 4 */
```

---

### 6. Dynasty List (General)
**URL:** `https://i.pinimg.com/1200x/da/81/f0/da81f03c65e31a7372f374aa99d63737.jpg`  
**Location:** Line 477 in CSS  
**Applied to:** `.dynasty-list` class  
**Effect:** Background for general dynasty list section

```css
.dynasty-list {
  background: url('https://i.pinimg.com/1200x/da/81/f0/da81f03c65e31a7372f374aa99d63737.jpg') 
              center center no-repeat;
}
```

---

### 7. Queen Dynasty
**URL:** `https://i.pinimg.com/1200x/54/93/9f/54939f460dcd12fa1c7069c9d7efb55b.jpg`  
**Location:** Line 488 in CSS  
**Applied to:** `.queen-dynasty` class  
**Effect:** Background for queen lineage section

```css
.queen-dynasty {
  background: url('https://i.pinimg.com/1200x/54/93/9f/54939f460dcd12fa1c7069c9d7efb55b.jpg') 
              center center no-repeat;
}
```

---

### 8. Pride Dynasty
**URL:** `https://i.pinimg.com/1200x/47/43/3b/47433b5856d19bc0fd0bdecb243320cb.jpg`  
**Location:** Line 499 in CSS  
**Applied to:** `.pride-dynasty` class  
**Effect:** Background for king lineage section

```css
.pride-dynasty {
  background: url('https://i.pinimg.com/1200x/47/43/3b/47433b5856d19bc0fd0bdecb243320cb.jpg') 
              center center no-repeat;
}
```

---

### 9. Achievements
**URL:** `https://i.pinimg.com/736x/fd/ac/3b/fdac3be26dbb437e00e71613907678b7.jpg`  
**Location:** Line 510 in CSS  
**Applied to:** `.achievements` class  
**Effect:** Background for achievements section

```css
.achievements {
  background: url('https://i.pinimg.com/736x/fd/ac/3b/fdac3be26dbb437e00e71613907678b7.jpg') 
              center center no-repeat;
}
```

---

### 10. Showcase
**URL:** `https://i.pinimg.com/736x/f3/d8/5e/f3d85e59ba0eb6e58024cb98d26f3b25.jpg`  
**Location:** Line 521 in CSS  
**Applied to:** `.showcase` class  
**Effect:** Background for showcase section

```css
.showcase {
  background: url('https://i.pinimg.com/736x/f3/d8/5e/f3d85e59ba0eb6e58024cb98d26f3b25.jpg') 
              center center no-repeat;
}
```

---

### 11. Beetle Book
**URL:** `https://i.pinimg.com/1200x/03/37/04/0337048534044c24ce61fcd7d00aad92.jpg`  
**Location:** Line 532 in CSS  
**Applied to:** `.beetle-book` class  
**Effect:** Background for beetle collection section

```css
.beetle-book {
  background: url('https://i.pinimg.com/1200x/03/37/04/0337048534044c24ce61fcd7d00aad92.jpg') 
              center center no-repeat;
}
```

---

## 📋 Summary

✅ **All 11 image URLs are integrated into the CSS file**  
✅ **Each image is applied to its designated section**  
✅ **All images use appropriate CSS properties (background-size: cover, proper positioning)**  
✅ **Images are ready to display when CSS is applied to Lioden den**

---

## 🎨 How Images Work

### Automatic Images:
- **Main Background** - Applied to entire page automatically
- **Featured Lion** - Applied to cave page featured lion section automatically

### HTML-Based Images:
All other images require their respective HTML sections to display:
- Use the HTML from `GetaTheme_552029_html.txt`
- Copy the section you want (e.g., pregnant-lionesses, queen-dynasty)
- Paste into your Lioden den HTML
- The image will appear as the background for that section

---

## 🔍 How to Verify Images

1. **Open:** `cssfiles/GetaTheme_552029.css`
2. **Search for:** Each image URL
3. **Confirm:** Image is present and correctly formatted
4. **Result:** All images are integrated! ✅

---

**Status:** ✅ All requested images are already integrated in the CSS  
**File:** `cssfiles/GetaTheme_552029.css` (826 lines)  
**Last Updated:** November 25, 2025  

*Ave Caesar! All images are ready for the Empire!* ⚔️🦁👑
