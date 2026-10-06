# static/files

Drop non-image static files here (e.g. `tj-gunther-resume.pdf`). This directory is copied as-is to the built site by the `static/files` passthrough in `.eleventy.js`.

The Resume page ([pages/resume.md](../../pages/resume.md)) expects a PDF at `static/files/tj-gunther-resume.pdf` (see the `resumePdf` front-matter field). Until that file exists, the "Download PDF" button is simply omitted from the page.
