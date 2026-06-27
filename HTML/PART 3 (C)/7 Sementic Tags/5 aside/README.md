# 🏷️ 5 aside

## 📚 Is Folder Ka Maqsad
Yeh folder **Semantic Tag: `<aside>`** ke baare mein hai. Aside tag ka istemal website ke sidebar, related content, ya aisi information ke liye hota hai jo main content se indirectly related ho.

---

## 📁 Files Overview

```
5 aside/
├── 5 aside.html        (Practice file showing main content and an aside sidebar)
└── README.md           (This file)
```

---

## 🎯 Topics Covered

### 1. **Aside Tag Basics**
`<aside>` tag search engines aur screen readers ko batata hai ke ye content main article ka hissa nahi hai, balke usse related izafi (extra) information hai. Ye `<div>` tag ka ek behtar semantic alternative hai sidebars banane ke liye.

```html
<main>
    <article>
        <h2>Main Topic</h2>
        <p>Main content goes here...</p>
    </article>
</main>

<aside>
    <h3>Related Links</h3>
    <ul>
        <li>Link 1</li>
        <li>Link 2</li>
    </ul>
</aside>
```

### 2. **Common Use Cases**
- **Sidebars** (jaise blog ke side par categories ya related posts).
- **Advertisements** (Ads).
- **Author biography** (writer ke baare mein maloomat).
- **Glossary terms** (alfaz ke mani aur tafseel).
- **Pull quotes** (article ke andar kisi khaas line ya quote ko highlight karna).

---

## 📝 Summary
Is folder mein banai gayi practice file mein ek taraf `<main>` tag ke andar article likha gaya hai, aur dusri taraf `<aside>` tag ke andar us se related links aur author ki info di gayi hai taake ek asal website ki tarah lagay (is layout ke liye basic CSS flexbox use kiya gaya hai).
