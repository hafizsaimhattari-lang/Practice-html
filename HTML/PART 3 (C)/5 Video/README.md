# 🏷️ 5 Video

## 📚 Is Folder Ka Maqsad
Yeh folder **HTML5 `<video>` Tag** ke baare mein hai. Is tag ke zariye hum apni website mein local ya external videos embed aur play kar sakte hain, bina kisi third-party plugin (jaise Flash) ke.

---

## 📁 Files Overview

```
5 Video/
├── 1 video add.html    (Practice file for video embedding)
├── [video file].mp4    (Sample video file for testing)
└── README.md           (This file)
```

---

## 🎯 Topics Covered

### 1. **Video Tag Basics**
`<video>` tag video ko webpage par dikhane ke liye use hota hai. Iske andar `<source>` tag istemal karke hum video ki file (src) aur type batate hain.

```html
<video width="640" height="360" controls>
    <source src="gojo-purple-aura.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

### 2. **Important Attributes**
- `controls`: Video par play, pause, aur volume ke buttons show karta hai.
- `autoplay`: Page load hotay hi video khud chalne lagta hai.
- `loop`: Video khatam hone ke baad dobara shuru ho jata hai.
- `muted`: Video ki aawaz band (mute) kar deta hai.
- `width` & `height`: Video ka size set karta hai.
- `poster`: Video play hone se pehle jo image (thumbnail) nazar aata hai.

---

## 📝 Summary
HTML5 ne video add karna intahai asaan kar diya hai. Ab humein sirf `<video>` tag use karna hota hai. Hamesha `controls` attribute zaroor add karein taake user video ko khud play/pause kar sake.
