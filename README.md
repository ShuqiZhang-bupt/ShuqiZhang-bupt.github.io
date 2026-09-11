# Shuqi Zhang - Academic Homepage

A responsive, English-language academic homepage built with plain HTML and CSS. No framework, JavaScript, external fonts, or build step is required.

## Files

- `index.html`: About, Personal Qualities, Education, Research Interests, Selected Projects, Honors, and Technical Skills
- `style.css`: desktop, mobile, keyboard-focus, and print styles
- `assets/files/resume.pdf`: current English resume, compiled from the approved LaTeX template
- `assets/files/transcript.pdf`: transcript PDF used by the top navigation and GPA link
- `.nojekyll`: tells GitHub Pages to serve the files directly

The transcript and resume are served from `assets/files/` so the homepage can be shared as a link rather than as separate email attachments.

## Local preview

From this directory, run `python -m http.server 8000 --bind 127.0.0.1`, then open `http://127.0.0.1:8000/`. Alternatively, open `index.html` directly in a browser.

## Update content

Edit the text in `index.html`. Keep the research and project descriptions tied to verified experience. Update the current year of study as needed. Only add project links and images when real materials are available.

All contact links use `2025210817@bupt.cn`.

PDF links and GitHub open in a new tab. Their accessible labels announce this behaviour. The project description distinguishes the team's system and technical results from Shuqi's confirmed personal contributions.

## Update the resume

Replace `assets/files/resume.pdf` with the latest approved English PDF using the same filename. The homepage link will remain unchanged. The Chinese resume and transcript are not included.

The resume's GPA links to `https://shuqizhang-bupt.github.io/assets/files/transcript.pdf`, the intended public transcript URL after GitHub Pages deployment.

## Add the transcript

When replacing the transcript, copy the user-supplied PDF, byte-for-byte, to `assets/files/transcript.pdf`. Preserve the original PDF without compression or conversion. Then check both the top Transcript link and Education GPA link in the local preview before publication.

Once the site is deployed, the intended permanent resume URL is:
`https://ShuqiZhang-bupt.github.io/assets/files/resume.pdf`

## Publication status

This is a local draft. No push or deployment has been performed. Review the homepage and resume content before publishing. When authorized, this repository can be served by GitHub Pages from the root of the `main` branch.

## Design reference

The information hierarchy takes inspiration from Yubo Huang's academic homepage (https://yubohuangai.github.io/) and the concise academic-homepage tradition associated with Jon Barron. HTML and CSS are written for this site; personal content and source code are not copied from either reference.
