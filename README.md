# Overleaf-Interactive-Template

Overleaf template for writing a thesis, seminar paper, working paper, or homework assignment, paired with a matching Beamer presentation template. Includes a built-in introduction to basic LaTeX/Overleaf usage.

The idealistic goal: anyone writing a thesis or seminar paper for a course in economics or other social sciences should be able to use this template to get started -- and, along the way, gain enough LaTeX knowledge to display everything they wish, without needing to consult outside resources.

One thing I tried to do differently: the introduction is built directly into the Overleaf document itself, rather than a separate guide. In the middle panel you see the LaTeX code being explained, and in the right panel you see the corresponding output it produces -- so you don't have to switch back and forth between a tutorial and your own project. I also tried to document the preamble in reasonable detail, explaining what each included package does and why it's there. It's not exhaustive, but every step is at least commented on.

It's also meant to be a practical template that can be adapted to different university requirements -- theme color, fonts, logo, and chapter structure are all easy to change.

## What is in it

This repository contains two templates that share the same bibliography, color theme, and structure:

- A standard document template (`Template_main.tex`) for thesis, seminar paper, working paper, or homework text
- A matching Beamer slides template (`Template_slides.tex`) for presenting the same content

Both templates include their own introduction section explaining how to use them, so you can learn the relevant LaTeX/Beamer basics directly inside the document you're editing.

## How to Use This Template (No GitHub Experience Needed)

1. Click the green "Code" button above the file list on this page. (Alternatively, click on Template v.1.0.0 on the right panel, just below "Releases"). 
2. Select "Download ZIP."

**Note for Safari users:** Safari automatically unzips downloaded files. If this happens, right-click the extracted folder in Finder and select "Compress" to create a `.zip` file before uploading it to Overleaf.

(Same for any other instance you get a folder after downloading instead of a .zip, just re-zip before going to Step4)


4. Go to Overleaf, click "New Project," then "Upload Project."
5. Select the ZIP file you just downloaded.
6. Overleaf will open the project automatically. Follow the instructions in `Template_main.tex` from there.

## Next Step: Getting Started in Overleaf

1. Open the project in Overleaf.
2. Decide whether you need the document template, the slides template, or both.
3. To switch between them, click the template you want to activate (default: `Template_main`), press the three buttons on the right, and select "Set as Main Document."
4. If you only need one, delete the other template and its associated files. Keep `bibliography_setup.tex` and `references.bib` either way (needed by both templates), and `beamercolorthemeTheme.sty` if you're keeping the slides template.

For the full walkthrough, read the introduction section inside `Template_main.tex`. For a presentation-specific walkthrough (assumes you've read the main document's intro), see `Template_slides.tex`.

## Background

This is based on the workflow I developed over the past three years. It works for me, and I wrote it because I feel LaTeX is often treated as something you're just expected to know until suddenly it's a requirement. The goal is to make the basic concepts approachable and give you a template you can actually use, not just read about.

## License / Usage

Feel free to share this template with anyone and edit it as you like. Just don't sell it or brand it as your own.

## Contact

If you want to suggest edits, report mistakes, or propose additions:

- Noah Mund (on all relevant social media apps)
- [noah.mund@icloud.com](mailto:noah.mund@icloud.com)
- [www.astudentsnote.de](https://www.astudentsnote.de) (to see what else I do)
