# 🖼️ 3 (img) Image Tag - Complete Media Guide
## Images Embed Karna aur Optimize Karna

---

## 📚 Is Folder Ka Maqsad

**Images** - web ko visually appealing banate hain!
Yeh folder mein images embed karna seekha: absolute paths, relative paths, responsive images, aur accessibility.

---

## 📁 Files

```
3 (img) Image Tag/
├── 1 (img) Absolute link.html       (External images)
├── 2 (img) Relative link.html       (Local images)
└── 3 (img) project-by-chat-gpt.html (Project application)
```

---

## 🎯 Topics Covered

### 1. **Basic Image Tag**

**Syntax:**
```html
<img src="path/to/image.jpg" alt="Description">
```

**Required Attributes:**
- `src` = Image path (zaroori)
- `alt` = Alternative text when image can't load (zaroori)

**Optional Attributes:**
- `width` = Width in pixels or percentage
- `height` = Height in pixels or percentage
- `title` = Tooltip text
- `class` = CSS class
- `id` = Unique identifier

---

### 2. **Absolute URLs** - Web Se Images

Complete web address se images:

```html
<!-- CDN from -->
<img src="https://rukminim2.flixcart.com/image/480/640/.../photo.jpg" 
     alt="Product photo">

<!-- Direct link -->
<img src="https://example.com/images/logo.png" 
     alt="Company logo">

<!-- Stock photos -->
<img src="https://unsplash.com/photos/random.jpg" 
     alt="Random photo">
```

**Advantages:**
- Kisi bhi website se use kar sakte
- CDN se fast loading
- Update automatically

**Disadvantages:**
- Internet dependency
- Slower than local
- External site dependency

---

### 3. **Relative URLs** - Local Files

Apne folder se images:

**Formats:**
```html
<!-- Same folder -->
<img src="image.jpg" alt="Image">

<!-- Sub-folder -->
<img src="images/photo.jpg" alt="Photo">

<!-- Parent folder -->
<img src="../images/photo.jpg" alt="Photo">

<!-- Root folder -->
<img src="/images/photo.jpg" alt="Photo">
```

**Folder Structure:**
```
website/
├── index.html
├── images/
│   ├── logo.png
│   ├── banner.jpg
│   └── product/
│       └── item1.jpg
└── pages/
    └── about.html
```

**From different locations:**
```html
<!-- From index.html -->
<img src="images/logo.png" alt="Logo">

<!-- From pages/about.html -->
<img src="../images/logo.png" alt="Logo">
```

---

### 4. **Image Dimensions**

```html
<!-- Fixed pixels -->
<img src="photo.jpg" alt="Photo" width="300" height="200">

<!-- Responsive (percentage) -->
<img src="photo.jpg" alt="Photo" width="100%" height="auto">

<!-- With style -->
<img src="photo.jpg" alt="Photo" style="max-width: 500px; height: auto;">
```

**Best Practice:**
```html
<!-- Flexible width, fixed aspect ratio -->
<img src="photo.jpg" 
     alt="Photo" 
     width="100%" 
     height="auto">
```

---

### 5. **Alt Text** - Accessibility

Alt text **zaroori** hai:

```html
<!-- Good alt text -->
<img src="dog.jpg" alt="Brown dog playing in park">

<!-- Bad alt text -->
<img src="image.jpg" alt="image">

<!-- Descriptive -->
<img src="chart.png" alt="Sales chart showing 50% growth in Q1">

<!-- Decorative (empty alt) -->
<img src="divider.png" alt="">
```

**Alt Text Guidelines:**
- Descriptive aur meaningful
- Keyword relevant (SEO)
- 125 characters se kam
- Question answer kare: "Kya hai?"

---

### 6. **Images as Links**

Image ko clickable banao:

```html
<a href="/product.html">
    <img src="product.jpg" alt="Product photo">
</a>

<!-- With styling -->
<a href="/gallery.html" class="gallery-link">
    <img src="thumbnail.jpg" alt="Gallery thumbnail">
</a>
```

---

### 7. **Responsive Images**

Mobile aur desktop par sab jagah sahi dikhne:

```html
<!-- Simple responsive -->
<img src="image.jpg" 
     alt="Description"
     style="max-width: 100%; height: auto;">

<!-- With max-width limit -->
<img src="image.jpg" 
     alt="Description"
     style="max-width: 500px; width: 100%; height: auto;">

<!-- Picture element (advanced) -->
<picture>
    <source media="(max-width: 600px)" srcset="small.jpg">
    <source media="(max-width: 1200px)" srcset="medium.jpg">
    <img src="large.jpg" alt="Image">
</picture>
```

---

### 8. **Image Optimization**

**File Size:**
- JPG = Photos (lossy compression)
- PNG = Graphics (lossless)
- WebP = Modern (smaller size)
- SVG = Vector (scalable)

**Optimization Tips:**
```html
<!-- Optimized size -->
<img src="photo-optimized.jpg" 
     alt="Photo"
     width="800"
     height="600">

<!-- Progressive loading -->
<img src="photo.jpg" 
     alt="Photo"
     loading="lazy">
```

---

## ✅ Concepts Covered

- [ ] Basic image syntax
- [ ] Absolute URLs (web)
- [ ] Relative URLs (local)
- [ ] Width aur height
- [ ] Alt text (accessibility)
- [ ] Images as links
- [ ] Responsive images
- [ ] Optimization

---

## 🎯 Real-World Examples

### Product Gallery:
```html
<div class="gallery">
    <a href="/product1.html">
        <img src="prod1-thumb.jpg" alt="Product 1">
    </a>
    <a href="/product2.html">
        <img src="prod2-thumb.jpg" alt="Product 2">
    </a>
</div>
```

### Blog Post:
```html
<article>
    <h1>Blog Title</h1>
    <img src="featured.jpg" 
         alt="Featured image for blog post"
         style="max-width: 100%; height: auto;">
    <p>Content...</p>
</article>
```

### User Profile:
```html
<div class="profile">
    <img src="avatar.jpg" 
         alt="User avatar - Ahmed"
         width="100"
         height="100">
    <h2>Ahmed</h2>
</div>
```

---

## ❌ Common Mistakes

❌ Bad:
```html
<!-- No alt text -->
<img src="photo.jpg">

<!-- Large image, no sizing -->
<img src="huge-photo.jpg">

<!-- Wrong path -->
<img src="images/photo.jpg" alt="">
```

✅ Good:
```html
<!-- With alt text -->
<img src="photo.jpg" alt="Family photo">

<!-- Responsive -->
<img src="photo.jpg" 
     alt="Family photo"
     style="max-width: 100%; height: auto;">

<!-- Correct path -->
<img src="../images/photo.jpg" alt="Family photo">
```

---

## 📊 Image Type Comparison

| Type | Use | Size | Support |
|------|-----|------|---------|
| JPG | Photos | Medium | All browsers |
| PNG | Graphics | Larger | All browsers |
| WebP | Modern | Smallest | Most browsers |
| SVG | Scalable | Varies | Modern browsers |
| GIF | Animations | Large | All browsers |

---

## ✅ Best Practices

```
✅ Always use alt text
✅ Optimize file size
✅ Use correct format
✅ Responsive sizing
✅ Lazy loading for many images
✅ Descriptive filenames
✅ Proper folder structure
```

---

## 📝 Checklist

- [ ] Absolute URLs use kiye
- [ ] Relative URLs use kiye
- [ ] Alt text properly likha
- [ ] Dimensions set kiye
- [ ] Responsive banaya
- [ ] Images as links use kiye
- [ ] Different formats try kiye

---

**Status:** ✅ Images Master!
**Next Folder:** 4 Practice QS Solve →
