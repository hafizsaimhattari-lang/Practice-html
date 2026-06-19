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
- Line break deta hai.
- New line par le jata hai.
- Iska closing tag nahi hota.
- Example idea: `Hello<br>World`

## 8) Horizontal Line
- `<hr>`
- Page ya section ke beech line banata hai.
- Sections ko alag dikhane ke liye use hota hai.
- Iska bhi closing tag nahi hota.
- Example idea: heading aur list ke darmiyan divider

## 9) Text Styling Tags Practiced

### `<b>`
- Text ko bold karta hai.
- Important lafz highlight karne ke liye use hota hai.
- Example idea: `This is <b>important</b>`

### `<i>`
- Text ko italic karta hai.
- Emphasis ya special style dene ke liye use hota hai.
- Example idea: `This is <i>important</i>`

### `<u>`
- Text ke neeche line lagata hai.
- Highlight ya emphasis ke liye use hota hai.
- Example idea: `This is <u>important</u>`

## 10) HTML Entities Learned

HTML entities special characters ko safely likhne ke kaam aate hain.

### Common entities
- `&lt;` = `<`
- `&gt;` = `>`
- `&amp;` = `&`
- `&quot;` = `"`
- `&apos;` = `'`
- `&nbsp;` = non-breaking space

### Why entities are used
- Jab special character browser ko normal text ki tarah dikhana ho.
- Jab `<` aur `>` jese symbols page par likhne hon, tag ki tarah nahi.

### Example ideas
- `5 &lt; 10`
- `A &amp; B`
- `He said &quot;Hello&quot;`

## 11) Attributes Learned So Far
- `style="..."`
- `title="..."`
- `lang="..."`

## 12) Style Attribute Values Learned So Far
- `background-color: ...;`
- `color: ...;`
- `font-family: ...;`
- `font-size: ...;`
- `text-align: ...;`

## 13) Important Notes
- Attributes usually come in `name="value"` form.
- Attributes are written in the start tag.
- Some tags do not need an end tag, like `<br>` and `<hr>`.
- Lowercase tag names and attribute names are better practice.
- Quotes around attribute values are better practice.
- `href` is used for links.
- `src` is used for image source.
- `alt` is important for images.
- `style` is used for simple styling.
- `title` shows tooltip text when you hover the mouse.

## 14) What I Can Revise From This List
- Basic page structure
- Headings and paragraphs
- Bold, italic and underline text
- Line break and horizontal line
- Links
- Ordered and unordered lists
- Images
- Attributes
- HTML entities
- Simple styling with `background-color` and `color`


## 15) Formatting Tags Aur Text Style Wale Tags

Ye tags text ko khubsurat, samajhne layak, aur kabhi kabhi meaning ke sath style dene ke kaam aate hain. Inka kaam sirf decoration nahi hota, balkeh kuch tags text ke matlab ko bhi batate hain.

### `<b>`
- Yeh text ko motay yani bold style mein dikhata hai.
- Aksar important lafz ko highlight karne ke liye use hota hai.
- Iska matlab zaroori nahi ke yeh semantic ho, lekin visually ye text ko zyada strong bana deta hai.
- Example soch: agar tum kisi lafz ko zyada ubhar kar dikhana chaho to `<b>` use hota hai.

### `<strong>`
- Yeh bhi text ko bold ki tarah dikhata hai.
- Lekin `<b>` se farq yeh hai ke `<strong>` text ki ahmiyat bhi batata hai.
- Yani browser aur screen reader ko signal milta hai ke yeh lafz important hai.
- Agar tum kisi sentence ka aham hissa highlight karna chaho to `<strong>` best hota hai.

### `<i>`
- Yeh text ko tedha yani italic style mein dikhata hai.
- Yeh sirf style ke liye bhi use hota hai aur kabhi kabhi special lafz ke liye bhi.
- Example ke taur par kisi term, naam, ya emphasis ko alag dikhane ke liye use hota hai.
- Is se text thora alag aur nazuk lagta hai.

### `<em>`
- Yeh bhi text ko italic jaisa dikhata hai.
- Lekin `<i>` se zyada meaning deta hai.
- Is ka matlab hota hai ke is lafz par emphasis hai, yani isay zor se samjho.
- Agar tum kisi jumlay ke andar kisi lafz ko stress dena chaho to `<em>` use hota hai.

### `<u>`
- Yeh text ke neeche line lagata hai.
- Aksar kisi important lafz ko underline karne ke liye use hota hai.
- Lekin isay bohat zyada istemal karna achi practice nahi hoti, kyun ke internet par underline aksar links ke sath confuse hota hai.
- Is liye yeh zyada tar sirf highlight ya special marking ke liye use hota hai.

### `<ins>`
- Yeh inserted yani add kiya gaya text dikhata hai.
- Is ke neeche bhi aksar line aati hai.
- Jab kisi text ko baad mein add kiya gaya ho ya change show karna ho to yeh tag use hota hai.
- Yeh sirf underline jaisa nahi, balkeh ek meaning bhi deta hai ke text naya add hua hai.

### `<mark>`
- Yeh text ko highlight karta hai, jaise marker se line highlight ki ho.
- Yeh bohat useful hota hai jab tum kisi lafz ko foran nazar mein lana chaho.
- Example ke taur par revision notes mein ya important points mein use hota hai.
- Is ka color aksar peelay marker jaisa hota hai.

### `<small>`
- Yeh text ko chhota karta hai.
- Aksar extra note, copyright line, ya chhoti information ke liye use hota hai.
- Example: footer mein chhoti si line likhni ho to yeh tag kaam aata hai.
- Is se text kam important ya secondary feel deta hai.

### `<sup>`
- Yeh text ko upar uthata hai.
- Is ka use powers, mathematical exponent, ya footnote type writing ke liye hota hai.
- Example socho 2 ka square likhna ho to 2 ke baad jo chhota upar wala number aata hai, woh `<sup>` hota hai.
- Science aur maths mein yeh bohat kaam aata hai.

### `<sub>`
- Yeh text ko neeche utharta hai.
- Is ka use chemical formulas ya neeche likhne wali notation ke liye hota hai.
- Example ke taur par pani ka formula likhte waqt H2O mein 2 neeche hota hai, woh `<sub>` ka kaam hai.
- Science notation mein yeh bohat important tag hai.

### `<abbr>`
- Yeh short form yani abbreviation ke liye use hota hai.
- Aksar is ke sath `title` attribute lagaya jata hai taake full form hover par dikh jaye.
- Example ke taur par HTML ka full meaning ya kisi organization ka naam samjhane ke liye yeh useful hota hai.
- Yeh accessibility aur learning dono ke liye acha tag hai.

### `<kbd>`
- Yeh keyboard input dikhane ke liye use hota hai.
- Jab kisi key ka naam ya keyboard se type hone wali cheez likhni ho to yeh tag use hota hai.
- Example socho: agar tum likho ke file save karne ke liye koi key dabani hai, to keyboard input ko alag style mein dikhane ke liye `<kbd>` use hota hai.
- Yeh tutorials aur guides mein bohat kaam aata hai.

### `<pre>`
- Yeh preformatted text dikhata hai.
- Is mein spaces aur line breaks same rehte hain.
- Is ka use code, poem, ya aisi writing ke liye hota hai jahan asli spacing bachani ho.
- Agar tum code ko as it is dikhana chaho to `<pre>` sab se useful hota hai.

### `<br>`
- Yeh line break deta hai.
- Is ka matlab text ko next line par le jana hota hai.
- Is ka closing tag nahi hota.
- Isay zyada tar paragraph ke andar ya chhoti line break ke liye use kiya jata hai.

### `<hr>`
- Yeh horizontal line banata hai.
- Is ka kaam sections ko visually alag karna hota hai.
- Yeh bhi empty tag hai yani is ka closing tag nahi hota.
- Notes, pages, aur sections ke darmiyan divider banane ke liye bohat useful hai.

## 16) Style Attribute Aur Title Attribute

### `style`
- Yeh HTML element ko style dene ke kaam aata hai.
- Is ke andar background color, text color, text alignment, font size, aur bohat si simple styling ki ja sakti hai.
- `style` attribute inline styling ke liye use hota hai.
- Example idea: kisi heading ko dark blue aur center mein lana.

### `title`
- Yeh extra information dikhane ke kaam aata hai.
- Jab mouse kisi element par hover karta hai to chhota sa tooltip nazar aata hai.
- Yeh images, links, paragraphs, headings aur bohat se elements mein use ho sakta hai.
- Learning aur accessibility dono mein help karta hai.

## 17) In Tags Ka Short Yaad Rakhne Ka Tareeqa
- `<b>` aur `<strong>` bold ke liye.
- `<i>` aur `<em>` italic ya emphasis ke liye.
- `<u>` aur `<ins>` underline jaisi line ke liye.
- `<mark>` highlight ke liye.
- `<small>` chhote text ke liye.
- `<sup>` upar wala text ke liye.
- `<sub>` neeche wala text ke liye.
- `<abbr>` short form samjhane ke liye.
- `<kbd>` keyboard key dikhane ke liye.
- `<pre>` spacing aur code ko as it is rakhne ke liye.
- `<br>` line break ke liye.
- `<hr>` section divider ke liye.
- `style` simple design ke liye.
- `title` extra tip ya tooltip ke liye.

## 18) Revision Mein Kya Kya Yaad Hona Chahiye
- Kis tag ka kaam text ko decorate karna hai.
- Kis tag ka kaam meaning dena hai.
- Kis tag ka kaam sirf line break ya divider dena hai.
- Kis tag ke sath `title` best lagta hai.
- Kis tag ke sath `style` se design diya jata hai.
- Kis tag se code ya spacing as it is rehti hai.
- Kis tag se highlight, emphasis, ya importance show hoti hai.

## 19) Chhoti Si Summary
- Formatting tags text ko achi shape aur meaning dete hain.
- Kuch tags sirf look change karte hain.
- Kuch tags meaning bhi batate hain.
- `br` aur `hr` empty tags hain.
- `style` aur `title` attributes bohat common aur useful hain.
- Roman Urdu mein in sab ko samajh kar practice karoge to yaad bohat behtar rahega.

## 20) In Formatting Tags Ki Practical Samajh

### `<b>` aur `<strong>` ka farq
- Dono text ko bold jaisa dikhate hain.
- `<b>` zyada tar sirf look ke liye hota hai.
- `<strong>` meaning bhi batata hai ke yeh text important hai.
- Agar tum sirf style dena chaho to `<b>`.
- Agar text ki ahmiyat show karni ho to `<strong>`.

### `<i>` aur `<em>` ka farq
- Dono italic jaisa style dete hain.
- `<i>` zyada tar visual style ke liye hota hai.
- `<em>` emphasis yani zor dene ke liye hota hai.
- Agar kisi lafz ko alag style mein dikhana ho to `<i>`.
- Agar kisi lafz par zor dena ho to `<em>`.

### `<u>` aur `<ins>` ka farq
- Dono neeche line jaisa effect dete hain.
- `<u>` sirf underline look deta hai.
- `<ins>` batata hai ke yeh text baad mein add kiya gaya hai.
- Agar bas underline chahiye to `<u>`.
- Agar change ya addition ka meaning chahiye to `<ins>`.

### `<mark>` ka use
- Is se text highlight hota hai.
- Important line, revision point, ya special lafz ko ubharne ke liye bohat acha hai.
- Notes mein is ka use bohat useful hota hai.

### `<small>` ka use
- Is se text chhota dikhta hai.
- Aksar footer, note, warning, ya extra detail ke liye use hota hai.
- Agar tum secondary information dikhana chaho to yeh tag useful hota hai.

### `<sup>` aur `<sub>` ka use
- `<sup>` text ko upar karta hai.
- Yeh powers, exponent, aur footnote type writing mein kaam aata hai.
- `<sub>` text ko neeche karta hai.
- Yeh chemistry aur formulas mein bohat useful hota hai.

### `<abbr>` ka use
- Yeh short form ko samjhata hai.
- Aksar `title` ke sath use hota hai.
- Is se full form hover par dikh sakti hai.
- Yeh learning ke liye bohat acha tag hai.

### `<kbd>` ka use
- Yeh keyboard input dikhane ke liye hota hai.
- Jab tutorial mein kisi key ka naam likhna ho to kaam aata hai.
- Is se user ko pata chalta hai ke koi key press karni hai.

### `<pre>` ka use
- Is tag mein spacing aur line breaks waise ke waise rehte hain.
- Code dikhane ke liye bohat useful hai.
- Poem, address, ya structured text ke liye bhi use hota hai.
- Is ke andar HTML text ko apni asli shape mein rakhta hai.

## 21) Kaun Sa Tag Kis Kaam Ke Liye Yaad Rakho
- `<b>` = bold look
- `<strong>` = important bold text
- `<i>` = italic look
- `<em>` = emphasized italic text
- `<u>` = underline look
- `<ins>` = added text
- `<mark>` = highlighted text
- `<small>` = chhota text
- `<sup>` = upar wala text
- `<sub>` = neeche wala text
- `<abbr>` = short form
- `<kbd>` = keyboard key
- `<pre>` = preformatted text
- `<br>` = line break
- `<hr>` = horizontal divider

## 22) Practice Karte Waqt Kya Dekhna Chahiye
- Kya tag sirf style de raha hai?
- Kya tag meaning bhi de raha hai?
- Kya text line ke andar reh raha hai?
- Kya text next line par ja raha hai?
- Kya spacing apni original form mein reh rahi hai?
- Kya hover par extra information aa rahi hai?
- Kya text ko highlight karna hai?
- Kya text ko importance deni hai?

## 23) Yaad Karne Ka Asaan Tareeqa
- Agar text ko strong banana ho to bold related tags dekho.
- Agar text ko incline ya emphasis deni ho to italic related tags dekho.
- Agar text ko highlight karna ho to mark.
- Agar text ko chhota karna ho to small.
- Agar formula ya notation ho to sup aur sub.
- Agar short form ho to abbr.
- Agar keyboard key likhni ho to kbd.
- Agar code ya spacing bachani ho to pre.
- Agar line todni ho to br.
- Agar divider banana ho to hr.

## 24) Final Roman Urdu Summary
- Yeh saare formatting tags text ko behtar dikhane aur samjhane ke kaam aate hain.
- Kuch tags sirf look change karte hain.
- Kuch tags meaning bhi batate hain.
- `style` se design aur `title` se extra tooltip milta hai.
- `br` aur `hr` empty tags hain.
- Roman Urdu mein inka matlab samajh kar practice karna bohat zaroori hai.
- Agar in sab ko projects mein use karo to yaad pakki ho jati hai.
- Ye revision note ab formatting tags ke liye complete reference ki tarah use ho sakta hai.

## 25) Chhoti Si Summary
- Formatting tags ka kaam text ko style dena, highlight karna, aur us ka matlab behtar samjhana hota hai.
- Kuch tags sirf dekhne mein style dete hain aur kuch tags meaning bhi batate hain.
- `<b>` aur `<strong>` bold ke liye use hote hain.
- `<i>` aur `<em>` italic ya emphasis ke liye use hote hain.
- `<u>` aur `<ins>` underline jaisa effect dete hain.
- `<mark>` text ko highlight karta hai.
- `<small>` chhota text dikhata hai.
- `<sup>` upar wala text dikhata hai aur `<sub>` neeche wala text.
- `<abbr>` short form ko samjhata hai.
- `<kbd>` keyboard key ke liye hota hai.
- `<pre>` code ya spacing ko jaisa ka taisa rakhta hai.
- `<br>` line break deta hai.
- `<hr>` section divider banata hai.
- `style` se simple design lagti hai.
- `title` se mouse hover par extra information milti hai.
- In tags ko bar bar practice karne se yaad bohat mazboot ho jati hai.
- Agar yeh sab ek page mein samajh aa jayein to HTML formatting ka bada hissa clear ho jata hai.

## 26) End Note
- Yeh file ab revision ke liye poori tarah kaam ki ja sakti hai.
- Isay baar baar dekh kar practice karo.
- Jitni zyada practice, utni zyada yaad-dasht strong hogi.

