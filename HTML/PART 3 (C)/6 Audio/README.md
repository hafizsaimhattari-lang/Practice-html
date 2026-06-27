# 🏷️ 6 Audio

## 📚 Is Folder Ka Maqsad
Yeh folder **HTML5 `<audio>` Tag** ke baare mein hai. Is tag ke zariye hum apni website mein sound, music, ya koi bhi audio file embed aur play kar sakte hain bina kisi extra plugin ke.

---

## 📁 Files Overview

```
6 Audio/
├── 1 audio add.html    (Practice file for audio embedding)
├── [audio file].wav    (Sample audio file for testing)
└── README.md           (This file)
```

---

## 🎯 Topics Covered

### 1. **Audio Tag Basics**
`<audio>` tag webpage par sound files lagane ke liye use hota hai. Isme bhi video ki tarah `<source>` tag use kar ke audio file ka path diya jata hai.

```html
<audio controls>
    <source src="music.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
```

### 2. **Important Attributes**
- `controls`: Audio player ke buttons (play, pause, timeline, volume) show karta hai.
- `autoplay`: Page load hote hi automatically gaana ya aawaz shuru ho jati hai. (Browsers aksar isko block karte hain jab tak user interact na kare).
- `loop`: Audio bar bar repeat hota rehta hai.
- `muted`: Aawaz band rakhta hai.

---

## 📝 Summary
Audio file add karna theek video ki tarah hi asaan hai. Standard practice ye hai ke hamesha MP3 format use kiya jaye kyun ke wo almost tamam browsers ko support karta hai (lekin hum ne yahan WAV format ki file bhi include ki hai test karne ke liye).
