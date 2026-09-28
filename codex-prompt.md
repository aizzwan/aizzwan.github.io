Build my personal website in this repository. The repo already contains profile.md (my content) and an /images folder (my photos).

## Tech
- Plain static site: index.html, styles.css, and a small script.js only if truly needed. No frameworks, no build step, no npm.
- Must run as-is on GitHub Pages from the repository root.
- Load IBM Plex Serif, IBM Plex Sans and IBM Plex Mono from Google Fonts, with system fallbacks.
- Use only the images in /images. No stock photos, no hotlinked images.
- Do not edit profile.md.

## Source rules
- profile.md is the only source of facts. Do not invent or embellish roles, numbers, dates, skills or quotes, and do not round numbers up.
- Keep the two skills groups in section 8 separate and labelled exactly as in profile.md.
- Before writing code, list any fact you needed but could not find in profile.md, then continue without it. Do not fill gaps yourself.

## Concept: "The Circular"
Style the page like a central bank policy document: numbered sections, clause numbering, and footnote-style citations where every proof number links to a footnote. Calm, precise, credible. No marketing tone, no emoji, no gradients, no parallax, no animated counters.

## Structure (one page, in this order)
1. Document header: reference line "Ref: AIZ/2026/01 · Issued [build date] · Version 1.0", my name, the site headline, the short bio, and images/portrait.jpg as a square portrait.
2. §1 Summary: a table of the proof points from profile.md section 2, each with a footnote marker.
3. §2 Experience: roles as numbered clauses (2.1, 2.2…), most recent first, max 3 bullets each.
4. §3 Projects: from section 4. Show the BNM Regulatory Document Assistant first, with an "In progress" label.
5. §4 Leadership & community: the table from section 5, then talks and recognition, with excel-workshop-ampang.jpg, ukm-leadership-talk-certificate.jpg and mangrove-volunteering.jpg as captioned figures.
6. §5 Writing: the three featured pieces, each showing its opening line and a link.
7. §6 Education & credentials: education, then the certifications table with a "Verify" link where a URL exists.
8. Schedule A: Contact. Linktree link only. No contact form, no email address.
9. Footnotes: numbered, and each one says which part of my experience the number comes from.

## Visual system
- Colours: background #F5F7F8, text #14213D, muted text #55607A, rules #D5DAE2, accent #B8322A used ONLY for section numbers and footnote markers.
- Type: IBM Plex Serif for headings, IBM Plex Sans for body, IBM Plex Mono for the reference line, section numbers, table figures and footnotes.
- Body text max about 65 characters wide. Generous white space. Thin rules between sections.
- Photos: natural colour, small corner radius, a caption in mono under each, and the alt text from profile.md section 9.

## Quality
- Mobile-first. Single column on phones, tables scroll sideways inside their own container, and the page itself never scrolls sideways.
- Semantic HTML, keyboard-accessible links with visible focus, colour contrast at WCAG AA or better.
- Page title "Amir Izzwan Abu Hasan", plus a meta description built from the headline, and Open Graph tags using portrait.jpg.
- Compress nothing and rename nothing in /images.

## Also create
- README.md explaining what the site is, how to run it locally (open index.html), and how it is deployed (GitHub Pages from main, root).

When done, give me a short summary: the files you created, anything from profile.md you left out and why, and anything I should check by eye.
