# LaTeX Templates — ICSE / ISC Mathematics (v2)

Five templates built on the [sagar-* style files](https://github.com/sagart23/latex-styles-sagar) (v2.1).

| File | Use |
|---|---|
| `10M_80.tex` | ICSE Class 10, Mathematics, 80 marks |
| `12M_80.tex` | ISC Class 12, Mathematics, 80 marks (A 20 / B 14 / C 21 / D 25) |
| `test.tex` | Class test (exam class) |
| `article.tex` | Worksheets and simple documents (student copy) |
| `notes.tex` | Notes (teacher copy: hints, answers and teacher-only text visible) |

## Requirements
1. TeX Live / MiKTeX 2022 or newer.
2. The style files installed in your TEXMF tree (see the styles README). Nothing else to copy.
3. `draftwatermark` (ships with TeX Live and MiKTeX).

## Using a template
1. Copy the file into your project and rename it.
2. Edit the **EDIT THIS BLOCK** at the top (title, date, class, marks, time, watermark).
3. Fill in the questions. For multiple choice use `oneparchoices` (options in one line) or `choices` (one per line), whichever the question needs.
4. Compile **twice** (page totals such as "Page 1 of N" need a second run), with `pdflatex`, `lualatex` or `xelatex`.

LuaLaTeX/XeLaTeX give Libertinus fonts automatically (via `sagar-fonts`). pdfLaTeX keeps Latin Modern. The same file builds in both, so the old separate `*Lua` templates are no longer needed.

## Teacher copy with answers
Exam papers: uncomment `\printanswers` near the top (the old templates had the `answers` class option switched on, which would print solutions on a student copy). Notes/worksheets: change `[student]` to `[teacher]` in `\documentclass`.

## Marks check (12M)
`12M_80.tex` writes `*** Total marks: 80 in 20 questions ***` to the log on the second run. Check it after editing.

## Logos
`10M_80`/`12M_80` use `clogo` and `cajcs.JPG`. Either keep them where `\graphicspath` points, or put both files in your TEXMF folder (for example `texmf/tex/latex/sagar-assets/`) and delete the `\graphicspath` line. Then any project in any subfolder finds them.

MIT License.
