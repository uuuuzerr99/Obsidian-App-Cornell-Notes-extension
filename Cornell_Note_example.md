---
cornell-layout:
  pageSize: A4
  margin: "2"
  headerHeight: "7"
  cuesWidth: "64"
  summaryHeight: "40"
  fontSize: 9pt
  fontFamily: "'Palatino Linotype', 'Book Antiqua', Palatino, serif"
  hideHeaders: true
  solidLine: true
  textWrapping: true
  floatSide: left
  justifiedText: true
  hyphenationLang: de
  codeScale: "0.7"
  mermaidScale: "0.3"
  tableScale: "0.8"
  elementSpacing: "2"
---

## Header 

## *Date:* xx-yy-zzzz  | *Class:* Computer Science 101 | *@Topic:* Supported Markdown Structures

## Cues %% Cues (reduce & recall) %%

Lorem ipsum dolor justo duo dolores et ea rebum. Dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent.


- [ ] Test: consetetur sadipscing elitr
	- [ ] Test 2

1. Do this
2. Do that 


- nulla facilisi
	- praesent luptatum erat, sed
![[JPG_Image.jpg|130]]
**.jpg (upper image) and .png file (below)**
![[PNG_Image.png|225]]
%% this is an inline comment, you can't see in the Cornell note. %%
%% 
We have comment blocks too... 
%%
**bold and one word *italic* mixed**
***Bold and italic*** 

**Escaping Markdown Syntax for:**  \*.file # ~

Tags: #tag

Obsidian-Syntax: https://help.obsidian.md/syntax
```textbox
This is a simple Textbox
```



**Script-size:**
 $$\scriptsize
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=(ad-bc)
$$

**Standard-size:**
$$ 
\sum_{i=1}^n i^2 = \frac{1}{2} n (n+1)
$$

**Large-size:**
$$ \large
\frac{\partial u}{\partial t}
 = p^2 \left( \frac{\partial^2 u}{\partial x^2}
+ \frac{\partial^2 u}{\partial y^2} 
+ \frac{\partial^2 u}{\partial z^2} \right)
$$
#### <font color="#ff0000">How to Install? → <mark style="background:#40a9ff">visit last page!</mark></font>
- This markdown document is typeset for A4 page dimensions
---
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue.

### Chemistry Formulas:

$\large \ce{^234_90Th -> ^0_-1\beta{} + ^234_91Pa}$ 

$\large \ce{A ->[H2O] B}$

$\large \ce{A-B=C#D}$ chem. bonding

$C_p[\ce{H2O(l)}] = \pu{75.3 J // mol K}$


**without LaTeX:**
a<sup>2</sup> + b<sup>2</sup> = c<sup>2</sup>
H<sub>2</sub>O (pure water)

# This is a heading 1
## This is a heading 2
### This is a heading 3
#### This is a heading 4
##### This is a heading 5
###### This is a heading 6

 --- 
 Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy est eirmod tempor ui blandit praesent luptat zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.






















- **Supported: .gif .webp .bmp & .svg**
![[Animation.gif|130]]
![[WEBP_Image.webp|150]]
![[BMP_Image.bmp|150]]
![[SVG_Image.svg|150]]

##### Cornell Note Sheet dimensions[^4] :
1 inch = 2.54 cm = 25.4 mm
- 2.5 inch = 63.5 mm (cues width)
- 6 inch = 152.4 mm (notes width)
- 2 inch = 50.8 mm (summary height)
[^4]: according to Walter Pauk (page format: US Letter)
[^5]: Euler identity

## Notes %% Notes (record) %%

**Lorem ipsum**
dolor sit <u>amet</u>, *consetetur* ~~sadipscing~~ elitr, sed diam ==nonumy== eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 


> text citation Lorem ipsum dolor sit amet, consetetur  sadipscing  elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril ==delenit== augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

This is an inline math expression $e^{2i\pi} = 1$.


| Math Formulas | Pictures | Mermaid Diagrams | Codeblocks |
| ------------: | -------- | ---------------- | :--------: |
| LaTeX         | 5 types  |  different types | syntax highlighting |
| inline        | + .gif   |  mermaid.js.org  |                     | 
**Table 1:** Eirmod tempor ui blandit praesent labore magna aliquyam erat, sed diam tempor ui blandit.
%% ___ %%      %% this comment on the left side: "%% ___ %%" is not part of traditional Obsidian Markdown. It creates an invisible line in the Cornell note Page View which helps with text alignment issues, if the text in the first table above is shorter. So that the following text can start at same height, even if there is free space above. %%

| Math Formulas | Pictures | Mermaid Diagrams | Codeblocks |
| :------------ | -------- | ---------------: | :--------: |
| LaTeX         | 5 types  |  different types | syntax highlighting |
| inline        | + .gif   |   mermaid.js.org |                     |
**Table 2:**  Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et aliquyam erat dolor sit amet, consetetur praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat sadipscing.
___
```java title:"long filename.cpp"
public class TreeNode<T> {
    T data;
    TreeNode<T> left;
    TreeNode<T> right;

    public TreeNode(T data) {
        this.data = data;
        this.left = null;
        this.right = null;
    }
}
```
**Java Code:**
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, dolore aliquyam sed diam voluptua.

```mermaid
quadrantChart
    title more @: mermaid.js.org/syntax/gantt
    x-axis Low Reach --> High Reach
    y-axis Low Engagement --> High Engagement
    quadrant-1 We should expand
    quadrant-2 Need to promote
    quadrant-3 Re-evaluate
    quadrant-4 May be improved
    Campaign A: [0.3, 0.6]
    Campaign B: [0.45, 0.23]
    Campaign C: [0.57, 0.69]
    Campaign D: [0.78, 0.34]
    Campaign E: [0.40, 0.34]
    Campaign F: [0.35, 0.78]
```

**Mermaid-Diagram:** [Mermaid Diagrams Syntax](https://mermaid.js.org/syntax/gantt)
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus. 
%%  COc(c1)cccc1C#N  %%
```smiles|0.3
COc(c1)cccc1C#N
```

**SMILES Chemistry Molecules Graphics:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam voluptua.

This is a simple footnote[^1]. This is a another footnote[^2]. This is a third footnote[^3].
[^1]: This is the referenced text.
[^2]: This is the referenced text too.
[^3]: This is the last referenced text.

---

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
![[PNG_Image.png|210]]
**Picture 1:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr,  sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
%% ___ %% 
___

### Math formula sizing is realized by using standard $\LaTeX$  syntax:
\tiny, \scriptsize, \small, \large or \huge within the math environment.

**Tiny:** 
$$\tiny
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=(ad-bc)
$$

**Small-size:**
$$\small 
\sum_{i=1}^n i^2 = \frac{1}{2} n (n+1)
$$

**Huge-size:**
$$ \huge
\frac{\partial u}{\partial t}
 = p^2 \left( \frac{\partial^2 u}{\partial x^2}
+ \frac{\partial^2 u}{\partial y^2} 
+ \frac{\partial^2 u}{\partial z^2} \right)
$$ 
___
## Chemistry Formulas with mhchem Package: [mhchem Syntax](https://ftp.snt.utwente.nl/pub/software/tex/macros/latex/contrib/mhchem/mhchem.pdf)
$\large \ce{Zn^2+
<=>[+ 2OH-][+ 2H+]
$\underset{\text{amphoteres Hydroxid}}{\ce{Zn(OH)2 v}}$
<=>[+ 2OH-][+ 2H+]
$\underset{\text{Hydroxozikat}}{\ce{[Zn(OH)4]^2-}}$
}$

# This is a heading 1
consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam 
## This is a heading 2
consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam 
### This is a heading 3
consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam 
#### This is a heading 4
consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam 
##### This is a heading 5
consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam 
###### This is a heading 6
consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam 

---
**Picture 1:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
![[PNG_Image.png|320]]
![[JPG_Image.jpg|280]]
**Picture 1:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr,  sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed. **Picture 2:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr,  sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut aliquyam erat, sed diam voluptua. 
___
> [!info]Lorem ipsum dolor sit amet, consetetur  ~~sadipscing~~  elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril ==delenit== augue duis dolore invidunt ut labore et *dolore* magna aliquyam erat, sed diam voluptua.

## How to install an commercial-community plugin, you bought?
- [ ] Create folder "cornell-notes" & unpack the .zip into it: main.js, styles.css, data.json & manifest.json
- [ ] Navigate to the Obsidian App plugins folder structure and copy folder with those 4 files in it to: "C:\...\Obsidian\Data\Obsidian Vault\.obsidian\plugins\cornell-notes" 
- [ ] In Obdisian App Settings: activate community plugins + in the installed section: activate this "Cornell Notes" extension. Restart Obsidian!
- Recommended Tutorial: [Brandon Boswell - How to Manually Install an Obsidian Plugin](https://www.youtube.com/watch?v=ffGfVBLDI_0)
### get files showcasing the capabilities & syntax of the extension → use it:
- [ ] [Download 3 files:](https://github.com/uuuuzerr99/Obsidian-App-Cornell-Notes-extension) PNG_Image.png, JPG_Image.jpg and Cornell_Note_example.md
- [ ] Paste them into your vault, same folder:  "C:\...\Obsidian\Data\Obsidian Vault\my_files" 
___
**This Obsidian App extension for Cornell Notes is supporting:**
- [x] **A4** (210 by 297 mm) which was used to create this note / .pdf file and
- [x] **US Letter** (8.5 by 11 inches)

**And it has some special tricks up its sleeve...**
- It's able to **create .pdf files with textlayer** or without  (**via Save html** or Print / PDF) .
  <u>**extra info**:</u> A .pdf file **with text layer** has embedded, selectable, searchable text, makes it "born-digital" or OCR'd for full functionality, while a .pdf **without a textlayer** is essentially an image.

## Summary %% Notes (reflect & review) %%

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
- This is an inline math expression $e^{2i\pi} = 1$.
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam. 
--- 
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit! 
![[JPG_Image.jpg|100]] Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit!

---
amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
- This is an inline math expression $e^{2i\pi} = 1$[^5].
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi amat.
