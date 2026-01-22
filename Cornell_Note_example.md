---
cornell-layout:
  pageSize: A4
  margin: "2"
  headerHeight: "6"
  cuesWidth: "65"
  summaryHeight: "37"
  fontSize: 9pt
  fontFamily: "'Palatino Linotype', 'Book Antiqua', Palatino, serif"
  hideHeaders: true
  solidLine: true
  textWrapping: true
  floatSide: left
  justifiedText: true
  hyphenationLang: de
  codeScale: "0.6"
  mermaidScale: "0.5"
  tableScale: "0.8"
  elementSpacing: "2"
---

## Header
**Date:** xx-yy-zz **Topic:** data structures

## Cues

#### <font color="#ff0000">How to Install? → <mark style="background:#40a9ff">visit last page!</mark></font>


Lorem ipsum dolor justo duo dolores et ea rebum.
- nulla facilisi
- praesent luptatum erat, sed diam dolor sit amet

![[JPG_Image.jpg|130]]
consetetur sadipscing.
![[PNG_Image.png|225]]

- [x] Test: consetetur sadipscing elitr, sede
- [ ] Test 2

%% here is an inline comments you can't see in the Cornell note. %%
%% 
We have comment blocks too... 
%%

- Test
- Test 2

1. Do this
2. Do that

**bold and one word *italic* mixed**
***Bold and italic*** 

**Escaping Markdown Syntax for:**  \*

Tags: #tag

clickable link:
https://help.obsidian.md/syntax 

```textbox
This is a simple Textbox
```

 ---
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue.

___
$$
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc
$$


$$
\frac{\partial u}{\partial t}
   = p^2 \left( \frac{\partial^2 u}{\partial x^2}
+ \frac{\partial^2 u}{\partial y^2} 
+ \frac{\partial^2 u}{\partial z^2} \right)
$$ 

$$
\sum_{i=1}^n i^2 = \frac{1}{2} n (n+1).
$$

without LaTeX:
a<sup>2</sup> + b<sup>2</sup> = c<sup>2</sup>
H<sub>2</sub>O (pure water)

# This is a heading 1
## This is a heading 2
### This is a heading 3
#### This is a heading 4
##### This is a heading 5
###### This is a heading 6

 --- 
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.










































##### Cornell Note Sheet dimensions[^4] :
1 inch = 2.54 cm = 25.4 mm
- 2,5 inch = 63.5 mm (cues width)
- 6 inch = 152.4 mm (notes width)
- 2 inch = 50.8 mm (summary height)
[^4]: according to Walter Pauk (page format: US Letter)
[^5]: Euler identity
## Notes

**Lorem ipsum**
dolor sit <u>amet</u>, *consetetur* ~~sadipscing~~ elitr, sed diam ==nonumy== eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 


> text citation Lorem ipsum dolor sit amet, consetetur  sadipscing  elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril ==delenit== augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

This is an inline math expression $e^{2i\pi} = 1$.



| Math Formulas | Pictures | Mermaid Diagrams | Codeblocks |
| ---: | --------- | --------- | :-------: |
| inline       | .png       |  different specialties | syntax highlighting |
| LaTeX      | .jpg        |   shown in the link  |  |
**Table 1:** Eirmod tempor ui blandit praesent labore magna aliquyam erat, sed diam tempor ui blandit.
%% ___ %%      %% this comment to the left side: "%% ___ %%" is not part of traditional Obsidian Markdown. It creates an invisible line in the Cornell note which helps with text alignment issues, if the text in the first table above is shorter . So that the following text can start at same height , even if there is freee space above. %%
| Math Formulas | Pictures | Mermaid Diagrams | Codeblocks |
| :--- | ---------: | :--------- | :-------: |
| inline       | .png       |  different specialties | syntax highlighting |
| LaTeX      | .jpg        |   shown in the link  |  |
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
    title Mermaid Diagrams: mermaid.js.org/syntax/gantt
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

**Mermaid-Diagram:** 
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus. 

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
$$
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc
$$


$$
\frac{\partial u}{\partial t}
   = p^2 \left( \frac{\partial^2 u}{\partial x^2}
+ \frac{\partial^2 u}{\partial y^2} 
+ \frac{\partial^2 u}{\partial z^2} \right)
$$ 

$$
\sum_{i=1}^n i^2 = \frac{1}{2} n (n+1).
$$

___
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
![[PNG_Image.png|340]]
![[JPG_Image.jpg|300]]
**Picture 1:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr,  sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed. **Picture 2:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr,  sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril delenit augue duis dolore invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut aliquyam erat, sed diam voluptua. 
___
> [!INFO]Lorem ipsum dolor sit amet, consetetur  ~~sadipscing~~  elitr, sed diam nonumy eirmod tempor ui blandit praesent luptatum zzril ==delenit== augue duis dolore invidunt ut labore et *dolore* magna aliquyam erat, sed diam voluptua.

## How to install this commercial-community plugin, you bought?
- [ ] unpack the .zip file and copy the four files: main.js, styles.css, data.json & manifest.json
- [ ] navigate to the Obsidian App plugins folder structure 
- [ ] create folder "cornell-modified", paste them in, activate extension and restart Obsidian.
"C:\...\Obsidian\Data\Obsidian Vault\.obsidian\plugins\cornell-grid"
- Recommended Tutorial: [Brandon Boswell - How to Manually Install an Obsidian Plugin](https://www.youtube.com/watch?v=ffGfVBLDI_0) 
### To see the example files showcasing the capabilities of the extension  
- [ ] paste PNG_Image.png, JPG_Image.jpg & Cornell_Note_example.md into your vault
- [ ] activate the extension.
- [ ] copy & paste the .md file and two images from github repo: 

___
**This Obsidian App extension for Cornell Notes is supporting:**
- [x] **A4** (210 by 297 mm) which was used to create this note / .pdf file and
- [x] **US Letter** (8.5 by 11 inches)

**And it has some special tricks up its sleeve...**
- it's able to create .pdf files *with* and without (via *Save html* or Print / PDF) textlayers.
  <u>**context info**:</u> A .pdf **with a text layer** has embedded, selectable, searchable text, makes it "born-digital" or OCR'd for full functionality, while a .pdf **without a text layer** is essentially an image.
## Summary

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
- This is an inline math expression $e^{2i\pi} = 1$.
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy. 
--- 
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit! 
![[JPG_Image.jpg|110]] Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit!

---
amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
- This is an inline math expression $e^{2i\pi} = 1$[^5].
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi amat.