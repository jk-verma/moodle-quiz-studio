# Moodle Quiz Studio

Upload a Word `.docx` or text-based PDF, review extracted MCQs, insert or paste figures in question and option editors, and export Moodle XML.

## Publish on GitHub Pages

Upload `index.html` to the root of a public GitHub repository and enable Settings > Pages > Deploy from a branch > main > root.

## Document format

Q1. What is shown?
A) First option
B) Second option
C) Third option
D) Fourth option
Answer: B
Marks: 2
Feedback: Explanation.

## Limitations

- The parser is heuristic; review all extracted questions, options, answers, feedback and marks.
- Word DOCX images are extracted. PDF page snapshots are available as reference, but automatic isolation and matching of individual figures is not guaranteed.
- Scanned PDFs require OCR and are not supported.
- Complex tables, columns, mathematical equations and layouts may need manual correction.
- The converter exports single-correct-answer multichoice questions, not all Moodle question types.
- CDN access is required for Mammoth.js and PDF.js.
- Import the exported file into a Moodle test question bank before using it in examinations.
