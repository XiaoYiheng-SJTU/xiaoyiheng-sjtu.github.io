# Yiheng Xiao — Academic homepage

A static English academic homepage for GitHub Pages. No build step, dependencies, or JavaScript is required.

## Publish on GitHub Pages

1. Create a public repository named `USERNAME.github.io`, replacing `USERNAME` with your GitHub account username (not your display name).
2. Upload the contents of this folder to the root of the repository, keeping all files together at the repository root. The root must contain `index.html`, `styles.css`, `cv.pdf`, and `.nojekyll`.
3. In **Settings → Pages**, select **Deploy from a branch**, then **main** and **/(root)**. Save.
4. Open the address shown in the Pages settings after the deployment completes.

The same files also work in a project repository because all asset links are relative.

## Update content

- Edit biography, paper titles, authors, statuses, or links directly in `index.html`.
- Change layout and colors in `styles.css`.
- Replace `cv.pdf` to update the CV while retaining its links.
- Replace a paper PDF at its existing path to update the document while retaining its links.
- To add a paper, copy an existing `<article class="publication">` into the appropriate category, update its text and both PDF links, and add the PDF at the repository root.
- The **Read** links open PDFs in a new browser tab. The **Download** links request a download using the same original PDF files.
- Keep submission statuses current. A submission should remain “Submitted to …” until it has been accepted.

`metadata.json` records the source content used to prepare the page. It is a reference file; the page is static, so edits to this JSON do not automatically change `index.html`.

## Content

The four research categories preserve the source ZIP classification: **synchronization**, **SDP**, **PDHG**, and **Online Preconditioning**. The site includes five papers, one PDF slide deck, and the original CV.

All PDFs were copied without modification. Do not add a code license to the research PDFs unless their authors have explicitly chosen one.

## Flat deployment layout

All six research PDFs are stored at the repository root for a single browser upload. The four research categories are preserved on the page.
