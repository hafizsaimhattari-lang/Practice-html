# HTML Learning List

## 1) Basic HTML Structure

- `<!DOCTYPE html>`
- `<html>`
- `<head>`
- `<body>`
- `<meta charset="UTF-8">`
- `<title>`

## 2) Headings and Paragraphs

- `<h1>`
- `<h2>`
- `<h3>`
- `<h4>`
- `<h5>`
- `<h6>`
- `<p>`

## 3) Text Formatting

- `<b>`

## 4) Links

- `<a>`
- `href="..."`
- `target="_blank"`

## 5) Lists

- `<ul>`
- `<ol>`
- `<li>`
- `type="1"`
- `type="A"`
- `type="a"`
- `type="I"`
- `type="i"`

## 6) Images

- `<img>`
- `src="..."`
- `alt="..."`
- `width="..."`
- `height="..."`
- `title="..."` (optional tooltip on image)

### What `<img>` does
- The `<img>` tag is used to display an image on the page.
- It is an empty element, so it does not need a closing tag.
- `img` ka full meaning image hota hai, yani yeh browser ko bolta hai ke page par tasveer dikhani hai.
- Image tag ke sath aksar `src`, `alt`, `width`, `height`, aur kabhi kabhi `title` use hota hai.
- Agar `src` na ho to image show nahi hogi.
- Agar image load na ho to `alt` text dikh sakta hai.

### Main image attributes
- `src` = image ka address ya path
- `alt` = image na khulay to jo text show ho
- `width` = image ki width
- `height` = image ki height
- `title` = mouse hover par chhoti information

### Image types you practiced

#### 1. Absolute image
- Full internet address use hota hai.
- Example idea: `src="https://..."`
- Ye image online website se aati hai.

#### 2. Relative image
- Sirf file ka naam ya folder ka path hota hai.
- Example idea: `src="image.jpg"`
- Ye image apne project folder se aati hai.

### Image with link
- Image ko clickable banane ke liye `<a>` tag ke andar `<img>` rakha jata hai.
- Phir image par click karne se link open hota hai.

### Important image rules
- `src` ke bina image show nahi hogi.
- `alt` lagana achi practice hai.
- `width` aur `height` se size control hota hai.
- Same image ko display bhi kar sakte ho aur clickable link bhi bana sakte ho.
- `href` link ke liye hota hai, `src` image ke liye hota hai. Dono alag kaam karte hain.

### Simple image examples you practiced mentally
- Normal image
- Absolute image from internet
- Relative image from your folder
- Clickable image
- Image inside `<a>` link

## 7) Line Break

- `<br>`

## 8) Attributes Learned So Far

- `style="..."` inline css
- `title="..."` box information
- `lang="..."` zuban ki setting

## 9) Style Attribute Values Learned So Far

- `background-color: ...;`
- `color: ...;`

## 10) Important Notes

- Attributes usually come in `name="value"` form.
- Attributes are written in the start tag.
- Some tags do not need an end tag, like `<br>`.
- Lowercase tag names and attribute names are better practice.
- Quotes around attribute values are better practice.
- `href` is used for links.
- `src` is used for image source.
- `alt` is important for images.
- `style` is used for simple styling.
- `title` shows tooltip text when you hover the mouse.

## 11) What I Can Revise From This List

- Basic page structure
- Headings and paragraphs
- Bold text
- Links
- Ordered and unordered lists
- Images
- Attributes
- Simple styling with `background-color` and `color`

