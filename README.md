Cornell Notes plugin for Obsidian App


**Development Status**: 🚧 Actively in development
- dark mode support
<img width="1912" height="1033" alt="grafik" src="https://github.com/user-attachments/assets/e92597ef-4a5d-47e8-a7ce-d73537d1665f" />

- not tried to use it on a tablet yet (so mobile App version might be developed too)

FEATURES:
- Zoom function: from 50% up to 100%
- offline mode (JavaScript libraries needed!)
- flexible and adaptable Layout (US-Letter or A4)
- choosing the width of Cues and Notes & height of header and summary: adaptable by menu!
- auto save settings (auto generated YAML front matter written into the .md file) for individual notes
- export to .pdf files, with textlayer (via .html file and Browser) and without textlayer
- cues content: more control of vertical positioning (alignment with corresponding notes content)

Supports: 
- Obsidian App, Desktop version only (you may need a big screen for working with it comfortably anyway)
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
- callout boxes: info, error, warning and tip: are not the original Obsidian callout boxes, with limited functionality, but with colors.
- citation box
- Tag Pills


INSTALLATION:

I'm integrating offline mode for this plugin, that's why four JavaScript libraries have to be downloaded so far. You put them in the Obsidian App plugins folder structure (where all the other plugins are), into a plugin folder named "cornell-notes". 

JavaScript LIBRARIES:

- Mermaid: (v10.9.1) https://unpkg.com/mermaid@10.9.1/dist/mermaid.min.js save as: mermaid.min.js
- MathJax: (v3.2.2 - tex-svg-full) https://unpkg.com/mathjax@3.2.2/es5/tex-svg-full.js save as: mathjax.min.js
- Smiles Drawer: (v2.1.7) https://unpkg.com/smiles-drawer@2.1.7/dist/smiles-drawer.min.js save as: smiles-drawer.min.js
- Prism: (v1.29.0) https://unpkg.com/prismjs@1.29.0/prism.js save as: prism.min.js

good to know:
Different builds/distributions of libraries often include unique configurations. Prism library for example is used for syntax highlighting code blocks in different programming languages like Java, C, etc. - so some languages might not be inclued in the basic version of the library. But you can configure and download them on this: https://prismjs.com/download#themes=prism&languages=markup+css+clike+javascript or other websites, to adapt them to your own needs. You can download them from this github repository too, so they will work with the capabilities of this plugin shown in the .pdf files above. mhchem support is currently limited to MathJax's tex-svg-full build.

Automatic saving of settings for each individual note & Obsidian (dark mode) with plugin light mode:
![](https://github.com/uuuuzerr99/Obsidian-App-Cornell-Notes-extension/blob/main/Animation2.gif)
Export to .pdf with textlayer (via .html and print to .pdf) and without textlayer (via Print / PDF):
![](https://github.com/uuuuzerr99/Obsidian-App-Cornell-Notes-extension/blob/main/Animation.gif)
Obsidian (light mode) with plugin dark mode:
![screenshot 752](https://github.com/user-attachments/assets/3fd4f31d-5643-4f1f-a295-6e1d7a6bbf0a)

Images:
All sample images have been generated with my prompts by Gemini AI.


Switzerland, February 19th 2026
