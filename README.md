# Year 12 Geography Revision Suite (Wenona)

Offline, self-contained HTML revision tools for Year 12 HSC Geography (NSW syllabus, first HSC 2025). Each file is a standalone page — no build step, no server, no external dependencies. Open any `.html` file directly in a browser, or host the folder as a static site (e.g. GitHub Pages).

## Pages

| File | Contents |
|---|---|
| `Geo12_Revision_Hub.html` | Start here — links to every page, syllabus dot point checklist, "how to revise" guidance |
| `Geo12_DirectiveTerms.html` | 18 directive terms glossary, flashcards, essay-writing strategy (CUBE, DAWSS), self-marking quiz |
| `Geo12_Topic1_Sustainability.html` | Topic 1 notes, flashcards, named case-study boxes, questions to practise, real exemplar answers |
| `Geo12_Topic2_Ecosystems.html` | Topic 2 notes, flashcards, questions to practise, real exemplar answers |
| `Geo12_Topic3_RuralUrban.html` | Topic 3 notes, flashcards, questions to practise, real exemplar answers |
| `Geo12_Q16_Skills.html` | Multiple-choice skills bank, Written Skills (Q16) bank, and construction guides (climate graphs, population pyramids, ternary graphs, cross sections, transects, précis maps) |
| `Geo12_Q17_GeographicalInvestigation.html` | Evaluating fieldwork, vocations, Environmental Impact Studies |
| `Geo12_ExamBuilder.html` | Generates a full practice exam (title page, MC, Q16, extended response with ruled writing lines) and prints it to PDF |

## How it works

- All content and question banks are embedded directly in each HTML file as JSON (`<script type="application/json">` blocks) — there's no database or backend.
- Student progress (flashcard position, quiz answers, written-practice mastery, saved name) is stored in the browser's `localStorage`, per file, per device. It is never sent anywhere.
- Every page can print to PDF via the browser's print dialog (Ctrl/Cmd+P), including a dedicated "Print flashcards" and "Print my answers" button where relevant.

## Updating content

Content lives as plain HTML/CSS/JS inside each file — open a file in any text editor to tweak wording, add questions, or restyle. There's no build pipeline to run.

## Publishing with GitHub Pages

1. Push this repository to GitHub.
2. In the repo's Settings → Pages, set the source to the `main` branch, root folder.
3. Share the resulting `https://<username>.github.io/<repo>/Geo12_Revision_Hub.html` link with students.
