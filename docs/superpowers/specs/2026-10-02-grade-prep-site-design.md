# Grade prep site design

Date: 2026-10-02

## Goal
Public, read-only page at gradeprep.doma.works that replaces the Google Doc as the link sent to clients booking a grade. The Google Doc stays as a fallback.

## Look
Same as access.doma.works (repo javaknees/doma-access-guide): grey #c6c6c6 background, DOMA logo, red #ea3f33 accents, system font, 700px column. One static index.html, no JavaScript, no images.

## Sections
1. Header and intro
2. Red callout: files must arrive at least 24 hours before the session
3. Two cards: Workflow 1 (original rushes), Workflow 2 (pre-conformed flat ProRes 4444). Stack on phones.
4. Key guidelines
5. Flat ProRes export reminders
6. CGI and VFX prep (EXR DWAA, LUMA mattes not Cryptomattes)
7. FOR GRADE folder layout
8. Contact your grade producer

## Copy
Wording from the Google Doc 1EXjNBRWylcpVogWP6jXp52gkojQt2QguHLf9XhbSNlk. Typos fixed. No em dashes.

## Hosting
Public repo javaknees/doma-grade-prep, GitHub Pages from main, CNAME gradeprep.doma.works.
DNS is third party (not Vercel). Jake adds: CNAME gradeprep -> javaknees.github.io

## After live
Replace the Google Doc link in ~/.claude/skills/grade-prep/SKILL.md with the new URL, only once the page loads and Jake confirms.
