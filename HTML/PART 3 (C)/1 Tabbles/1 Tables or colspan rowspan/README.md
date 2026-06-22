# 📊 1 Tables or Colspan Rowspan
## Table Cells Ko Merge Karna - Colspan aur Rowspan

<!-- 
    ====================================
    FOLDER DESCRIPTION
    ====================================
    Ye folder sirf colspan aur rowspan se related hai
    Yahan sab files mein tables ko merge kiya gaya hai
    
    Real-world examples:
    - Sports tables (Football scores)
    - School timetables
    - Billing invoices
    ====================================
-->

---

## 📚 Is Folder Ka Maqsad

**Colspan & Rowspan** - Multiple cells ko merge karke tables ko customize karna.

<!-- 
    Colspan = Column merge (Ek cell 2-3 columns tak spread)
    Rowspan = Row merge (Ek cell 2-3 rows tak spread)
-->

---

## 📁 Files

```
1 Tables or colspan rowspan/
├── 1 tabbale.html               (Basic table structure)
├── 2 table.html                 (Table with thead, tbody, tfoot)
├── 3 span (col&row).html        (Colspan aur rowspan examples)
├── 3 span practice col & row.png (Visual guide for colspan/rowspan)
├── 4 football scores span.html  (Football scores table with spans)
├── 4 football scores span.gif   (Football scores visual)
└── 5 timetable span practice.html (School timetable with spans)
└── 5 timetable span practice.png  (Timetable visual guide)
```

---

## 🎯 Key Concepts

### Colspan
```html
<!-- Ek cell 3 columns tak spread ho -->
<tr>
    <td colspan="3">Merged Cell</td>
</tr>
```

<!-- 
    COLSPAN EXPLANATION:
    - colspan="2" = Ye cell 2 columns le raha hai
    - colspan="3" = Ye cell 3 columns le raha hai
    - Zyada columns, zyada wide cell
-->

### Rowspan
```html
<!-- Ek cell 2 rows tak spread ho -->
<td rowspan="2">Merged</td>
```

<!-- 
    ROWSPAN EXPLANATION:
    - rowspan="2" = Ye cell 2 rows ko cover kar raha hai
    - rowspan="3" = Ye cell 3 rows ko cover kar raha hai
    - Zyada rows, zyada tall cell
-->

### IMPORTANT RULE 🔴
```
❌ Colspan ya rowspan khud se nayi rows ya columns create nahi karte!
✅ Ye sirf pehle se mojood rows/columns ke andar apni jagah gherte hain
```

<!-- 
    YE RULE BHOT IMPORTANT HAI!
    
    EXAMPLE:
    Agar table mein 3 rows hain aur ek cell mein rowspan="5" likha hai
    To 5 rows create nahi hongi - Error aayega!
    
    Ye sirf existing rows ko use karta hai.
    TABLE KO PLAN KARTE WAQT YE DHYAN RAKHNA PADTA HAI
-->

---

## 📝 Examples

### Football Scores Table
<!-- 
    Yahan colspan ka use karke:
    - Team ke names ko merge kiya
    - Total score ko merge kiya
    - Isse table zyada organized dikhta hai
-->
Colspan ka use karke scores table banaya - teams aur total columns ko merge kiya

### School Timetable
<!-- 
    Yahan rowspan ka use karke:
    - Same timing ke sab subjects ko merge kiya
    - Lab timing ko zyada height di
    - Period aur timing ko ek side rakhte hain (usually rowspan use hota hai)
-->
Rowspan ka use karke period timing ko merge kiya - same time ke sab subjects

---

## ✅ Learning Points

- [x] Colspan - columns ko merge karna
- [x] Rowspan - rows ko merge karna
- [x] Mixed colspan aur rowspan
- [x] Table structure (thead, tbody, tfoot)
- [x] Real-world examples (Football, Timetable)

<!-- 
    YE SAB FILES COMPLETE HAIN:
    ✅ Basic tables samajh gaye
    ✅ Colspan-rowspan clear ho gaya
    ✅ Real examples dekhe
    
    Next: Colgroup folder mein jaao!
-->

---

**Status:** ✅ Tables & Spans Complete

