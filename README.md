# AUI Summer School 2026

The website for Al Akhawayn University’s 2026 Summer School on **Industry 4.0 & Smart Manufacturing**.

The site presents the program, topics, instructors, partners, venue information, and registration details in a responsive single-page experience.

<!-- Add a full-page screenshot here. -->

## Built for

Al Akhawayn University in Ifrane  
School of Science & Engineering

## Features

- responsive event landing page;
- program and topic overview;
- instructor and partner sections;
- registration call to action;
- mobile navigation;
- custom visual system based on AUI colors;
- no build step or application runtime.

## Run locally

Clone the repository and serve the directory with any static file server:

```bash
git clone https://github.com/OmarTaheri/aui-summer-school.git
cd aui-summer-school
python -m http.server 8000
```

Open <http://localhost:8000>.

You can also open `index.html` directly, although a local server more closely matches production behavior.

## Maintenance

Most content currently lives in `index.html`. When updating the page:

1. verify dates, contacts, instructors, and partner names with the program owner;
2. optimize new images before committing them;
3. check desktop and mobile layouts;
4. verify keyboard navigation, contrast, headings, and alternative text;
5. test every registration and external link.

## Recommended next cleanup

- move CSS into `styles.css`;
- move interactive behavior into `script.js`;
- add Open Graph/social preview metadata;
- run Lighthouse and an automated accessibility check;
- add a deployment workflow;
- document who approves program-content changes.

## Attribution and use

Institutional names, logos, photographs, and program content may have separate owners and usage rules. Confirm authorization before reusing them outside this site.

No open-source code license is currently declared.
