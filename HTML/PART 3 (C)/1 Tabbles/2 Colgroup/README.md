# 🎨 2 Colgroup
## Table Columns Ko Style Karna - Colgroup Element

<!-- 
    ====================================
    COLGROUP EXPLANATION
    ====================================
    Colgroup ek powerful element hai jo poore columns ko style karta hai
    Bina har individual cell ko style kiye!
    
    Example use:
    - Report tables mein alternate colors
    - Invoice mein specific columns ka background
    - Dashboard tables mein important columns ko highlight karna
    ====================================
-->

---

## 📚 Is Folder Ka Maqsad

**Colgroup** - Poore column ko styling dena ek saath, bina har cell ko individually target kiye.

<!-- 
    Why Colgroup?
    
    ❌ Without Colgroup:
    <tr>
        <td style="background: yellow;">Data</td>
        <td style="background: yellow;">Data</td>
        <td style="background: yellow;">Data</td>
        ... (har row mein ye repeat hoga!)
    </tr>
    
    ✅ With Colgroup:
    <colgroup>
        <col style="background: yellow;">
        <col style="background: yellow;">
        <col style="background: yellow;">
    </colgroup>
    ... (ek baar likha, poora column style ho gaya!)
-->

---

## 📁 Files

```
2 Colgroup/
└── (Coming Soon...)
```

<!-- 
    Yahan aage examples add honge:
    - Simple colgroup
    - Multiple column styling
    - Colgroup with CSS classes
    - Responsive colgroup
-->

---

## 🎯 Colgroup Kya Hai?

`<colgroup>` element se hum table ke columns ko organize aur style kar sakte hain.

### Syntax
```html
<table>
  <colgroup>
    <col style="background-color: yellow;">
    <col span="2" style="background-color: red;">
  </colgroup>
  <tr>
    <td>Col 1</td>
    <td>Col 2</td>
    <td>Col 3</td>
  </tr>
</table>
```

<!-- 
    COLGROUP STRUCTURE:
    
    <colgroup>           ← Container jo columns ko group karta hai
        <col ...>        ← Ek ek column define karta hai
        <col span="2">   ← Ye 2 columns ko affect karta hai
    </colgroup>
    
    Har <col> = Ek column
    span="n" = N columns ko ek saath handle karo
-->

---

## 📝 Key Attributes

### `<col>` Tag Attributes

| Attribute | Maqsad | Example | Details |
|-----------|--------|---------|---------|
| `span` | Kitne columns ko affect karna | `<col span="2">` | Ek col 2+ columns handle kar sakta hai |
| `style` | CSS styling apply karna | `style="background-color:yellow;"` | Inline CSS likho |
| `class` | CSS class apply karna | `class="column-style"` | External CSS use karo |
| `id` | Column ko identify karna | `id="important-col"` | JavaScript ke liye useful |

<!-- 
    IMPORTANT NOTES:
    
    1. width style colgroup par kaam karta hai
       <col style="width: 50px;">
    
    2. text-align bhi set kar sakte ho
       <col style="text-align: center;">
    
    3. visibility hidden kar sakte ho (sirf style se)
       <col style="visibility: hidden;">
    
    4. border-styling kaam nahi karti colgroup par
       (tbody/tr par border lagana padta hai)
-->

---

## 💡 Fawaid (Benefits)

✅ Pura column ek baar style ho  
✅ CSS repeating code nahi - DRY principle  
✅ Multiple columns ko ek style se handle karna  
✅ Table ko professional dikhana  
✅ Maintenance easy hota hai  

<!-- 
    REAL WORLD EXAMPLES:
    
    1. Invoice Table:
       Col 1 = Item names (wide)
       Col 2 = Price (medium)
       Col 3 = Quantity (medium)
       Col 4 = Total (medium)
       
    2. Report Table:
       Col 1 = ID (narrow, gray)
       Col 2 = Name (wide, white)
       Col 3 = Status (medium, highlight karo)
       Col 4 = Date (narrow, gray)
    
    Colgroup se ye sab easily handle ho sakta hai!
-->

---

## 🤔 Rowgroup Kya Hota Hai? (Alternatives to Rowgroup)

HTML mein `<colgroup>` ke jaisa koi direct `<rowgroup>` element **nahi** hota. 
Lekin agar aap rows ko group karna chahte hain, toh iske liye HTML mein 3 special elements mojood hain jo row grouping ka kaam karte hain:

1. **`<thead>`** - Table ka header row group (Title waghera ke liye)
2. **`<tbody>`** - Table ka main data / body row group (Actual data ke liye)
3. **`<tfoot>`** - Table ka footer row group (Totals, summaries ke liye)

### Syntax (Row Grouping)
```html
<table>
  <!-- Header Group -->
  <thead>
    <tr>
      <th>Name</th>
      <th>Price</th>
    </tr>
  </thead>
  
  <!-- Body Group -->
  <tbody>
    <tr>
      <td>Item 1</td>
      <td>$10</td>
    </tr>
  </tbody>
  
  <!-- Footer Group -->
  <tfoot>
    <tr>
      <td>Total</td>
      <td>$10</td>
    </tr>
  </tfoot>
</table>
```

> **Note:** Aap CSS ki madad se `<thead>`, `<tbody>`, ya `<tfoot>` ko target kar ke poori rows ke group ko ek saath style de sakte hain.

---

## 📚 Colgroup Examples Banane Wale Hain

- [ ] Simple colgroup with colors
- [ ] Multiple colspans with different styles
- [ ] Responsive colgroup
- [ ] Real-world example (Invoice table)
- [ ] Colgroup with CSS classes
- [ ] Advanced styling techniques

<!-- 
    LEARNING PATH:
    
    1. Basic colgroup syntax samjho
    2. Span attribute sikho
    3. CSS styling practice karo
    4. Real examples dekho
    5. Own examples banaao!
-->

---

**Status:** 🔜 Coming Soon - Examples add honge
**Last Updated:** 2026-06-22

