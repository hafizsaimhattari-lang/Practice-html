# 📊 1 Tabbles - Complete Table Learning
## HTML Tables - Basic se Advanced Tak

<!-- 
    ====================================
    COMPLETE TABLES FOLDER
    ====================================
    Ye folder sab kuch HTML tables ke baare mein hai
    Basic structure se leke colspan/rowspan tak
    
    Sub-folders:
    1. Tables or colspan rowspan - Cells ko merge karna
    2. Colgroup - Columns ko style karna
    
    Real world examples:
    - Sports tables
    - School timetables
    - Billing/Invoice tables
    - Reports aur dashboards
    ====================================
-->

---

## 📚 Is Folder Ka Maqsad

**Tables** - Data ko rows aur columns ke format mein present karna.

<!-- 
    WHY TABLES ARE IMPORTANT:
    ✅ Structured data display
    ✅ Easy to read information
    ✅ Professional look
    ✅ Real-world usage - Reports, invoices, schedules
-->

---

## 📁 Folder Structure

```
1 Tabbles/
├── 1 Tables or colspan rowspan/     (Basic tables + colspan/rowspan merging)
├── 2 Colgroup/                      (Column styling with colgroup element)
└── README.md                        (This file)
```

<!-- 
    FOLDER ORGANIZATION:
    
    1. Tables or colspan rowspan/
       └─ Yahan basic tables aur merging techniques hain
       └─ Real-world examples (Football, Timetable)
    
    2. Colgroup/
       └─ Advanced styling for entire columns
       └─ DRY principle use karke CSS likho
-->

---

## 🎯 Complete Table Concepts

### 1️⃣ Basic Table Elements
```html
<table>           <!-- Table container -->
  <tr>            <!-- Table Row -->
    <td>Data</td>     <!-- Table Data (cell) -->
    <th>Header</th>   <!-- Table Header -->
  </tr>
</table>
```

<!-- 
    BASIC ELEMENTS EXPLANATION:
    - <table> = Poora table
    - <tr> = Ek row (Row mein multiple cells hote hain)
    - <td> = Normal cell (Data cell)
    - <th> = Header cell (Bold aur centered by default)
-->

### 2️⃣ Table Sections
```html
<table>
  <thead>...</thead>  <!-- Header rows -->
  <tbody>...</tbody>  <!-- Body rows -->
  <tfoot>...</tfoot>  <!-- Footer rows -->
</table>
```

<!-- 
    SEMANTIC STRUCTURE:
    
    <thead>  = Top part (Column names)
    <tbody>  = Middle part (Actual data - can be multiple)
    <tfoot>  = Bottom part (Total/Summary rows)
    
    YE SEMANTIC BANATA HAI AAPKA HTML!
    Screen readers ko samajhne mein aasan hota hai
-->

### 3️⃣ Colspan & Rowspan
```html
<td colspan="2">Merged Columns</td>
<td rowspan="3">Merged Rows</td>
```

<!-- 
    COLSPAN = Column merge
    colspan="2" = Ye cell 2 columns le raha hai
    
    ROWSPAN = Row merge  
    rowspan="3" = Ye cell 3 rows ko cover kar raha hai
    
    REMEMBER: Nayi rows/columns create nahi hote!
-->

### 4️⃣ Colgroup (Styling)
```html
<colgroup>
  <col style="background-color: yellow;">
  <col span="2">
</colgroup>
```

<!-- 
    COLGROUP BENEFIT:
    Pura column ko ek baar style karo
    Bina har cell ko individually target kiye
    
    Isse code clean aur maintainable rehta hai
-->

---

## 📂 Sub-folders

### 📊 1 Tables or colspan rowspan
Basic table structures اور colspan/rowspan examples
- Basic table (1 tabbale.html)
- Table with sections (2 table.html)
- Colspan & Rowspan (3 span files)
- Football scores example (4 football files)
- Timetable example (5 timetable files)

<!-- 
    YE FOLDER MEIN:
    ✅ Simple tables se shuru
    ✅ Colspan/rowspan basics
    ✅ Real-world examples
    ✅ Visual guides (Images/GIFs)
-->

### 🎨 2 Colgroup
Column styling اور colgroup element کے ساتھ
- Colgroup basic concepts
- Multiple column styling
- Real-world examples (آنے والے)

<!-- 
    YE FOLDER MEIN:
    🔜 Coming: Colgroup examples
    🔜 CSS styling techniques
    🔜 Professional table designs
-->

---

## 🔥 Important Rules

### Rule 1️⃣ - Colspan/Rowspan
```
⚠️ Colspan ya rowspan NAYI rows/columns create nahi karte
   Ye sirf existing rows/columns mein spread hote hain!
```

<!-- 
    CRITICAL RULE!!!
    
    WRONG:
    <table>
        <tr>
            <td rowspan="5">Cell</td>
            <!-- Sirf 2 cells aur -->
        </tr>
    </table>
    
    CORRECT:
    <table>
        <tr>
            <td rowspan="5">Cell</td>
            <td>Cell</td>
        </tr>
        <tr>
            <td>Cell</td>
        </tr>
        <tr>
            <td>Cell</td>
        </tr>
        <tr>
            <td>Cell</td>
        </tr>
        <tr>
            <td>Cell</td>
        </tr>
    </table>
    
    5 rows pehle se hone chahiye!
-->

### Rule 2️⃣ - Table Border
```html
<!-- CSS use karo styling ke liye -->
<style>
  table, th, td {
    border: 1px solid black;
    border-collapse: collapse;  /* Double border hatane ke liye */
  }
</style>
```

<!-- 
    BORDER STYLING:
    - border="1" (HTML attribute) - Purani method, avoid karo
    - CSS se likho (Modern way)
    - border-collapse: collapse; = Double borders ko hatane ke liye
-->

### Rule 3️⃣ - Semantic HTML
```
✅ <thead> - Header rows ke liye
✅ <tbody> - Content rows ke liye  
✅ <tfoot> - Footer/Total rows ke liye
❌ Sab kuch <tr><td> mein hi na likho!
```

<!-- 
    SEMANTIC HTML KA FAIDA:
    ✅ Better for SEO
    ✅ Accessibility (Screen readers)
    ✅ Code readable aur maintainable
    ✅ Professional standard
-->

---

## 💡 Real-World Examples

| File | Example | Use Case |
|------|---------|----------|
| Football scores | Colspan | Sports standings table |
| Timetable | Rowspan | School schedule |
| Billing | Colgroup + Colspan | Invoice format |

<!-- 
    REAL EXAMPLES:
    
    1. Football Table:
       Team names ko merge (colspan)
       Isse table organized lagta hai
    
    2. Timetable:
       Lab classes ke liye zyada time (rowspan)
       Period aur timing clear dikhta hai
    
    3. Billing:
       Item column wide (colgroup)
       Price columns align (colgroup)
       Total row footer (tfoot)
-->

---

## ✅ Learning Checklist

- [x] Basic table structure
- [x] Table rows aur columns
- [x] Table headers (thead, tbody, tfoot)
- [x] Colspan - columns merge
- [x] Rowspan - rows merge
- [x] Real-world examples
- [ ] Colgroup styling (In Progress)
- [ ] Advanced table designs

<!-- 
    LEARNING PROGRESS:
    ✅ Basics + Merging = COMPLETE
    🔄 Colgroup = IN PROGRESS
    🔜 Advanced = COMING SOON
    
    Next: Colgroup folder se examples explore karo!
-->

---

**Status:** 🔄 In Progress - Colgroup examples coming soon
**Last Updated:** 2026-06-22

---

## 📚 Further Learning

```
Next Topics:
→ Forms (PART 3 - Section 2)
→ CSS for Tables
→ Responsive Tables
→ Table Accessibility
```

<!-- 
    PROGRESSION:
    Current: HTML Tables ✅
    Next: Forms
    After: CSS for styling
    Future: JavaScript interactions
-->

