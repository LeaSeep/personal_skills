# personal_skills

Personal Claude skills, version controlled.

| Skill | Purpose |
|---|---|
| `writing/` | Drafting from bullet points and editing text in my style (papers, rebuttals, slides, casual) |

## Install / update in Claude
Zip the skill folder (e.g. `zip -r writing.zip writing`) and upload it under Skills in Claude settings, or ask Claude to propose the updated SKILL.md.

## Sources
The writing skill paraphrases principles from:
- J. Schimel, *Writing Science: How to Write Papers That Get Cited and Proposals That Get Funded* (OUP, 2012), via "Writing Science in a Sheet" (A. Burgin, 2016)
- Academic Writing Workshop, *Writer's Checklist*
- J. Morley, *Academic Phrasebank* (University of Manchester, 2018) - `writing/references/academic-phrasebank-2018.pdf`
- J. Hasenauer, *Scientific Paper Writing Checklist* (group-internal) - `writing/references/paper-checklist.md`

## Personal use only
This repository contains third-party material for personal use only. **Before making the repo public, remove:**
- `writing/references/academic-phrasebank-2018.pdf` (licence prohibits redistribution)
- `writing/references/phrasebank-index.md` (only useful with the PDF)
- `writing/references/paper-checklist.md` (group-internal document)

and delete them from the git history (e.g. `git filter-repo --path <file> --invert-paths`).
