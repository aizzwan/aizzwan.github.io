# The Circular — Amir Izzwan Abu Hasan

A single-page personal website styled as a policy circular. Built with semantic HTML and CSS; no JavaScript, framework, npm, or build step is required.

## Run locally

Open `index.html` in a browser. Google Fonts loads IBM Plex Serif, Sans, and Mono when online; system fonts provide offline fallbacks.

## Deploy with GitHub Pages

Push these files to the `main` branch of the `aizzwan.github.io` repository. In GitHub **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/ (root)**, and save. The site address is https://aizzwan.github.io/.

The local checkout has an unborn `master` branch and no remote. Publishing has not completed: local Git lacks its HTTPS helper, and the connected GitHub integration rejected the upload with HTTP 403 (Resource not accessible by integration). Grant the integration write access to this repository, or upload the files through GitHub, before enabling Pages.

## Content and photos

`profile.md` is an unchanged copy of the supplied source and the only source for biographical facts. Edit the HTML when updating the site; the Markdown is not loaded at runtime. Keep claims and footnotes aligned with the profile, and update the issue date when publishing a new version.

The four supplied photos are preserved under their original filenames in `images/`. Byte-for-byte copies also provide the filenames required by the website:

| Original | Website copy |
| --- | --- |
| 01-portrait.jpg | portrait.jpg |
| 02-ukm-leadership-talk-2025-10.jpg | ukm-leadership-talk-certificate.jpg |
| 06-mangrove-volunteering-2025-01.jpg | mangrove-volunteering.jpg |
| 07-excel-workshop-ampang-2024-12.jpg | excel-workshop-ampang.jpg |

No photo was compressed or modified. The supplied portrait is 600×900, rather than the 800×800 described in the profile; CSS displays it as a square. Other photographs retain their natural aspect ratios. Alt text comes verbatim from profile section 9.

## Editorial choices

- Experience roles are ordered by start date, newest first. The current banking role combines five source bullets into three, retaining their facts.
- Both skills groups retain their exact labels and appear under Experience.
- All three writing entries link to Linktree because individual URLs were not provided. The July 2024 entry is a description, not an invented quote.
- Four credentials have no verification URL in the source; their verification cells show a dash.
- Footnotes identify the supplied experience behind numerical claims. They are source annotations, not independent verification. The quoted June 2026 writing statistic has no underlying statistical source in the profile.

## Review before publishing

Check the portrait's square crop, certificate readability, phone layout, table scrolling, keyboard focus, and Linktree destinations. Social previews use the original portrait at `https://aizzwan.github.io/images/portrait.jpg`.

