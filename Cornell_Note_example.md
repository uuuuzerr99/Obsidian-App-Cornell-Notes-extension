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
  hyphenationLang: en
  codeScale: "0.75"
  mermaidScale: "0.35"
  tableScale: "0.75"
  elementSpacing: "2"
---

# Header 

## *Date:* xx-yy-zzzz  | *Class:* Computer Science 101 | *@Topic:* Supported Markdown Structures

# Cues %% Cues (reduce & recall) %%

Lorem ipsum dolor justo duo dolores et ea rebum. Dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent.



- [ ] Test: consetetur sadipscing elitr
	- [ ] Test 2



1. Do this
2. Do that 



- nulla facilisi
	- praesent luptatum erat, sed

![[JPG_Image.jpg|220]]
**.jpg (upper image) and .png file (below)**
![[PNG_Image.png|220]]
%% this is an inline comment, you can't see in the Cornell note. %%
%% 
We have comment blocks too... 
%%
**bold and one word *italic* mixed**
***Bold and italic*** 

**Escaping Markdown Syntax for:**  \*.file # ~

Tag-Pills: #tag

Obsidian-Syntax: https://help.obsidian.md/syntax
```textbox
This is a simple Textbox
```

%% ___ %%
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
- This markdown document is typeset for A4 page dimensions, rearrange content for US Letter!

--- %% Begin Cues Page 2 %%
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue.


 
<font color="#e36c09">Vertical content positioning in the cues section is essential!</font>
1) use 3+ empty lines to position content vertically in the cues section.
2) textwrapping can be deactivated locally in the cues section. Just use 2 empty markdown lines!

 
![[SVG_Image.svg|120]]
Made image small by using [["Image" |120px]], so global textwrapping rules are applied in the Cues area. This is achieved by inserting zero blank lines after image.
Compare this behavior with an identical .svg file and this [Markdown file](https://github.com/uuuuzerr99/Obsidian-App-Cornell-Notes-extension/blob/main/Cornell_Note_example.md): 
 
![[SVG_Image.svg|120]]


textwrapping is now <u>de</u>activated locally (by adding 2 empty markdown lines) while being activated globally! It's simple, intuitive and gives you maximum layout control.


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

 --- %% Begin Cues Page 3 %%
 Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy est eirmod tempor ui blandit praesent luptat zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.







- **Supported: .gif .webp .bmp & .svg**
![[Animation.gif|220]]
![[WEBP_Image.webp|220]]
![[BMP_Image.bmp|220]]
![[SVG_Image.svg|220]]





##### Cornell Note Sheet dimensions[^4] :
1 inch = 2.54 cm = 25.4 mm
- 2.5 inch = 63.5 mm (cues width)
- 6 inch = 152.4 mm (notes width)
- 2 inch = 50.8 mm (summary height)
A4 is ~ 3.5% larger in area than US Letter.

##### Suggestions for A4 dimensions:
- 60-70mm cues width
- 45-55mm summary height
[^4]: according to Walter Pauk (page format: US Letter)
[^5]: Euler identity

# Notes %% Notes (record) %%

**Lorem ipsum**
dolor sit <u>amet</u>, *consetetur* ~~sadipscing~~ elitr, sed diam ==nonumy== eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 


> text citation Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam. 
> • tempor ui blandit praesent luptatum zzril ==delenit== augue duis dolore invidunt ut labore et (A. de Saint-Exupéry)

This is an inline math expression $e^{2i\pi} = 1$.


| Math Formulas | Pictures | Mermaid Diagrams | Codeblocks |
| ------------: | -------- | ---------------- | :--------: |
| LaTeX         | 5 types  |  different types | syntax highlighting |
| + inline      | + .gif   |  mermaid.js.org  |                     | 
**Table 1:** Eirmod tempor ui blandit praesent labore magna aliquyam erat, sed diam tempor ui blandit.
%% ___ %%      %% this comment on the left side: "%% ___ %%" is not part of traditional Obsidian Markdown. It creates an invisible line in the Cornell note Page View which helps with text alignment issues, if the text in the first table above is shorter. So that the following text can start at same height, even if there is free space above. %%

| Math Formulas | Pictures | Mermaid Diagrams | Codeblocks |
| :------------ | -------- | ---------------: | :--------: |
| LaTeX         | 5 types  |  different types | syntax highlighting |
| + inline      | + .gif   |   mermaid.js.org |                     |
**Table 2:**  Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et aliquyam erat dolor sit amet, consetetur praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat sadipscing.
___
```java title:"filename.java"
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
**Mermaid-Diagram:** [Mermaid Diagram Syntax](https://mermaid.js.org/syntax/gantt)
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus. %% ___ %% 
%%  COc(c1)cccc1C#N  CC(=O)OC1=CC=CC=C1C(=O)O %%
```smiles|0.3
COc(c1)cccc1C#N
```
[**SMILES Chemistry Molecules Graphics:**](https://hunterheidenreich.com/notes/computational-chemistry/molecular-representations/smiles/) Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
This is a simple footnote[^1]. This is a another footnote[^2]. This is a third footnote[^3].
[^1]: This is the referenced text.
[^2]: This is the referenced text too.
[^3]: This is the last referenced text.

--- %% Begin Notes Page 2 %%

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, uptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
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

--- %% Begin Notes Page 3 %%
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
![[PNG_Image.png|320]]
![[JPG_Image.jpg|280]]
**Picture 1 | .png:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr,  sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed. 

**Picture 2 | .jpg:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr,  sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut aliquyam erat, sed diam voluptua.
___
> [!info]For: error (red), info (blue), warning (yellow) and tip (green)
> - eirmod tempor ui blandit praesent luptatum zzril ==delenit== augue dolore invidunt ut 
> 	- rabore et *dolore* magna ~~sadipscing~~  aliquyam erat, sed diam voluptua.
> labore eunt deus optima ipsum.

## How to install an commercial-community plugin, you bought?
- [ ] Create folder "cornell-notes" & unpack the .zip into it (4 files): main.js, styles.css, data.json & manifest.json
- [ ] Download 4 .js files here [go to README section:](https://github.com/uuuuzerr99/Obsidian-App-Cornell-Notes-extension) now copy them into folder "cornell-notes"
- [ ] Copy folder with those 8 files, navigate to the Obsidian App plugins folder structure and  put it into: "C:\...\Obsidian\Data\Obsidian Vault\.obsidian\plugins\cornell-notes" 
- [ ] In Obsidian App Settings: activate community plugins + in the installed section: activate this "Cornell Notes" extension. Now restart Obsidian!
- Recommended Tutorial: [Brandon Boswell - How to Manually Install an Obsidian Plugin](https://www.youtube.com/watch?v=ffGfVBLDI_0)
### get files showcasing the capabilities & syntax of the extension → use it:
- [ ] [Download 7 files:](https://github.com/uuuuzerr99/Obsidian-App-Cornell-Notes-extension) Animation.gif,  BMP_Image.bmp, WEBP_Image.webp, PNG_Image.png, JPG_Image.jpg, SVG_Image.svg,  and Cornell_Note_example.md 
- [ ] Paste them into your vault, same folder:  "C:\...\Obsidian\Data\Obsidian Vault\my_files_here" 
___
**This Obsidian App extension for Cornell Notes is supporting:**
- [x] **A4** (210 by 297 mm) which was used to create this note / .pdf file and
- [x] **US Letter** (8.5 by 11 inches [216 x 279mm])

**And it has some special tricks up its sleeve...**
- It's able to **create .pdf files with textlayer** or without  (**via Save html** or Print / PDF) .
  <u>**extra info**:</u> A .pdf file **with text layer** has embedded, selectable, searchable text, makes it "born-digital" or OCR'd for full functionality, while a .pdf **without a textlayer** is essentially an image.

# Summary %% Notes (reflect & review) %%

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. 
- This is an inline math expression $e^{2i\pi} = 1$.
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor erat, sed diam voluptua.
---  %% Begin Summary Page 2 %%
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit! 
![[JPG_Image.jpg|70]] Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

---  %% Begin Summary Page 3 %%
Amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
- This is an inline math expression $e^{2i\pi} = 1$[^5].
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi amat!
