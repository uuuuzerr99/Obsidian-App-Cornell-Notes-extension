Cornell Notes plugin for Obsidian App


**Development Status**: 🚧 Actively under construction:

- not tried to use it on a tablet yet (so mobile App version might be developed too)
- I'm still working on a few features - after all, there has to be something mysterious left to reveal!
- special prompts for specific tasks to support note taking in class (e.g. for creating LaTeX Code, diagrams, math plots)

⚠️ Don't use .pdf viewer of your browser to view the .pdf files above (if you want to see true graphic capabilites of this plugin)... Browser PDF viewers often make PDFs look bad because they prioritize fast loading and basic viewing over high-fidelity rendering, often using low-resolution previews to save memory. With a standard pdf viewer it looks crisp & clear & beautiful! 

<img width="1538" height="992" alt="grafik" src="https://github.com/user-attachments/assets/3bba1972-7d3e-48e3-a657-59af9c4076ca" />

**User Scenario: That makes complex real-time note taking for average skilled students possible, if not even fun!**

  AI Support for generating all kinds of plots: You're sitting in a math lecture, jotting down short, messy notes of what your teacher is writing on the board as he explains to the class how vector addition works. You just select your messy text and send it to an AI via shortcut. Some seconds later it appears as code in your .md note file as an svg, you scale it and it's done! Usually you would struggle taking notes in real-time on your laptop in a class, even wasting more time after class at home, just to get your notes done?!? Not anymore...  
![Animation3](https://github.com/user-attachments/assets/91488ffc-4ab3-413a-b64c-8bdf85459b3f)
The quality and duration for appearance varies quite a bit (this one needed 35 seconds to see the result), depends on the model and if it's free or not. I've tested it via openrouter API (which is for free) and for a paid model Google Gemini Pro too (but choose the smaller model gemini-2.5-flash for generating some of the .svg) - both works! As you can see in the Animation3.gif, there are other short, messy prompts (in German as I'm living in Switzerland) I've been testing: Inequalities, Solution Sets, quadratic and cubic equations... so far. You can use your local language too, like german, french, italian, english or whatever...

FEATURES:
- Support students with low level or even no LaTeX and SMILES skills (Middle Schoolers or Junior High Schoolers) to create formula and special syntax in and for their Cornell Notes. And make professionals even faster and more productive!
- dark mode support
- Zoom function: from 50% up to 100%
- offline mode (JavaScript libraries needed!)
- flexible and adaptable Layout (US-Letter or A4)
- choosing the width of Cues and Notes & height of header and summary: adaptable by menu!
- auto save settings (auto generated YAML front matter written into the .md file) for individual notes
- export to .pdf files, with textlayer (via .html file and Browser) and without textlayer
- cues content: more control of vertical positioning (alignment with corresponding notes content)
- possibility to create columns: usecase → sometimes you want or need 2 or 3 objects next to each other (text, code, picture or other types of content) and control the width to your needs too.
- Typographie: font sizes, fonts, justified text, wrap content, text floating left or right.
- page formats: portrait only

Supports: 
- Obsidian App, Desktop version only (you may need a laptop sized screen for working with it comfortably anyway)
- code blocks, with syntax highlighting for lots of programming languages
- mhchem package and SMILES (Simplified Molecular Input Line Entry System) for chemistry
- LaTeX for Math formula typesetting (inline too)
- footnotes representations
- picture file formats: .jpg, .png .webp .bmp & .svg + .gif
- tables
- Checkboxes
- Lists (numbered, not numbered)
- mermaid Diagrams (https://mermaid.js.org/syntax/examples.html)
- Textboxes
- callout boxes: now all 12 Obsidian types are supported (not the original Obsidian callout boxes, with limited functionality)
- callout boxes, custom: able to modify Title & color (Hex color notation: #FF0000 is red) https://www.color-hex.com/ > [!custom|#FF0000] My callout heading
- citation box
- Tag Pills
- Anki Export function: 
- Zotero Export function: You don’t want to double the effort importing tag-pills you already created in Obsidian PDF Cornell notes while importing it in Zotero — especially when you want your collection of Cornell Note files to be stored in zotero and need those Tags for future searches? Automate it: import a .ris entry (with file_title.md, author, Tags, date) into Zotero with a single shortcut, then attach the Obsidian plugin created .pdf file. Needs seconds, instead of minutes. This workaround is useful, as Zotero doesn’t allow imports of tags from keyword tagged .pdf files.


INSTALLATION:

I'm integrating offline mode for this plugin, that's why four JavaScript libraries have to be downloaded so far. You put them in the Obsidian App plugins folder structure (where all the other plugins are), into a plugin folder named "cornell-notes". 

JavaScript LIBRARIES:

- Mermaid: (v11.13.0) https://unpkg.com/mermaid@11.13.0/dist/mermaid.min.js save as: mermaid.min.js (needed for Anki export feature!)
- MathJax: (v3.2.2 - tex-svg-full) https://unpkg.com/mathjax@3.2.2/es5/tex-svg-full.js save as: mathjax.min.js
- Smiles Drawer: (v2.1.7) https://unpkg.com/smiles-drawer@2.1.7/dist/smiles-drawer.min.js save as: smiles-drawer.min.js 
  | Note: Standard SMILES is designed for compactness and often omits hydrogens. For full atom representation, use explicit hydrogen SMILES library (downloadable from my repo) or isomeric SMILES with detailed formatting.
- Prism: (v1.29.0) https://unpkg.com/prismjs@1.29.0/prism.js save as: prism.min.js

good to know:
Different builds/distributions of libraries often include unique configurations. Prism library for example is used for syntax highlighting code blocks in different programming languages like Java, C, etc. - so some languages might not be inclued in the basic version of the library. But you can configure and download them on this or other websites:
- https://prismjs.com/download#themes=prism&languages=markup+css+clike+javascript - with your programming languages included, just select and download
- https://docs.mathjax.org/en/latest/web/start.html#mathjax-components - with mhchem Package (needed for the usage of chemistry notation: example .md file) included in full version - further info: https://mhchem.github.io/MathJax-mhchem/ 

to adapt them to your own needs. You can download them from this github repository too, so they will work with the capabilities of this plugin shown in the .pdf files above. mhchem support is currently limited to MathJax's tex-svg-full build.

Automatic saving of settings for each individual note & Obsidian (dark mode) with plugin light mode:
![](https://github.com/uuuuzerr99/Obsidian-App-Cornell-Notes-extension/blob/main/Animation2.gif)
Export to .pdf with textlayer (via .html and print to .pdf) and without textlayer (via Print / PDF):
![](https://github.com/uuuuzerr99/Obsidian-App-Cornell-Notes-extension/blob/main/Animation.gif)
Obsidian (light mode) with plugin dark mode:
![screenshot 752](https://github.com/user-attachments/assets/3fd4f31d-5643-4f1f-a295-6e1d7a6bbf0a)

Images:
All sample images have been generated with my prompts by Gemini AI.


Switzerland, April 12th 2026
