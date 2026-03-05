---
cornell-layout:
  pageSize: Letter
  margin: "2"
  headerHeight: "7"
  cuesWidth: "64"
  summaryHeight: "40"
  fontSize: 9pt
  fontFamily: "'Palatino Linotype', 'Book Antiqua', Palatino, serif"
  hideHeaders: false
  solidLine: true
  textWrapping: true
  floatSide: left
  justifiedText: true
  hyphenationLang: de
  codeScale: "0.9"
  mermaidScale: "0.25"
  tableScale: "0.75"
  elementSpacing: "5"
---

# Header 

## *Date:* xx-yy-zzzz  | *Class:* Computer Science 101 | *@Topic:* US Letter, with Objects neighboring

# Cues 


# Notes 



<div class="cornell-flex-row" style="display: flex; gap: 5px; align-items: flex-start;">
**Script-size:** $$\scriptsize
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=(ad-bc)
$$

![[BMP_Image.bmp|205]]

| Math Formulas | Pictures | Mermaid Diagrams | Codeblocks    |
| ------------: | -------- | ---------------- | :-----------: |
| LaTeX         | 5 types  |  different types | syntax highlighting |
| + inline      | + .gif   |  mermaid.js.org  |                     | 
</div>

<div style="display: flex; gap: 0px; align-items: flex-start;">
```java
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

And positioning some text next to 
the two objects. For optimal use of 
space.

So let's look if it sums up to you: 
$\sum_{i=1}^n i^2 = \frac{1}{2} n (n+1)$

```mermaid|0.27
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
</div>


<div style="display: flex; gap: 0px; align-items: flex-start;">
![[PNG_Image.png|184]]
![[JPG_Image.jpg|184]]
![[Animation.gif|190]]
</div>

<div style="display: flex; gap: 10px; align-items: flex-start;">
**Pic_1:** You can do it with  
a text too! You've got to try.
**Pic_2:** Just some more text. 
The alignment is more difficult!
**Pic_3:** It's not perfect, but in the 
end it will work most of the time.
</div>

- Finetuning sizes of: pics, tables, formulas, diagrams make layouts look quite good. 
- Just with convenient input methods (buttons, sliders, shortcuts) or using standard Obsidian Syntax and the necessary code will appear in the markdown file at the right place. 







## A Matrix Multiplication trick[^1] :
<div class="cornell-flex-row" style="display: flex; gap: 5px; align-items: flex-start;">

$ \begin{array}{c|c} \phantom{\begin{matrix} Phantom \\ B \\ A \\ C \end{matrix}} & \begin{matrix} 13 & 14 & 15 \\ 16 & 17 & 18 \\ 19 & 20 & 21 \\ 22 & 23 & 24 \end{matrix} \\ \hline \begin{matrix} 1 & 2 & 3 & 4 \\ 5 & 6 & 7 & 8 \\ 9 & 10 & 11 & 12 \end{matrix} & \begin{matrix} 190 & 200 & 210 \\ 470 & 496 & 522 \\ 750 & 792 & 834 \end{matrix} \end{array} $ This method is taught in european schools and not straight forward to display in LaTeX. We have two matrices: A (3x4: 3 rows, 4 columns) with values from 1-12 and matrix B (4x3, 13-24). Matrix C (3x3, lower right) holds nine results. For more details on that matrix multiplication method: search for falk scheme videos online. Like this one here: [Falk schema:  A trick for matrix multiplications](https://youtu.be/3Y9aAliJeAc?t=213) 

</div>


[^1]: invented by Sigurd Falk: For 1-12 Matrix A: Multiply every row-entry by a corresponding column-entry (number of matrix B) and add them all up.  For matrix A * matrix B: 13-24 [Elements] = matrix C for results (190 up to 834). Calculation examples for some results in the C matrix (3x3): (1x13)+(2x16)+(3x19)+(4x22) = 190 | (5x14)+(6x17)+(7x20)+(8x23) = 496 | (9x13)+(10x16)+(11x19)+(12x22) = 750. Imagine drawing a line, connecting each matrix A element (row wise, left to right) to the corresponding matrix B element (column wise, top to bottom) an adding the four results up, which gives you one element of the result-matrix C. So you have to do this 9 times.

# Summary

<div style="display: flex; gap: 10px; align-items: flex-start;">
**Sum_A:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed 
diam nonumy tempor invidunt ut labore et dolore magna 
aliquyam erat, sed diam voluptua. At vero eos et accusam 
et justo duo dolores et ea rebum. Stet clita kasd gubergren, 
no sea takimata sanctus est. Lorem ipsum dolor sit amet. 
Lorem ipsum dolor sit amet, consetetur sadip.

**Sum_B:** Lorem ipsum dolor sit amet, consetetur sadipscing elitr, 
sed diam nonumy eirmod tempor invidunt ut labore et 
dolore magna aliquyam erat, sed diam voluptua. At vero 
eos et accusam et justo duo dolores et ea rebum. Stet 
clita kasd gubergren, no sea takimata sanctus est Lorem 
ipsum dolor sit amet. Lorem ipsum dolor sit amet, 
consetetur sadipscing elitr, magna aliquyam erat, sed 
diam voluptua.
</div>


