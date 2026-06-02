# Student Portfolio Template

A clean, multi-page digital portfolio for students to showcase work across **Math, Science, English, Social Studies, and Technology** — with images, downloadable files/documents, and reflections tied to college-, career-, and citizenship-readiness standards.

Built as plain HTML/CSS. **No build step, no frameworks.** Just edit and deploy.

---

## Quick start (try it locally)

Open `index.html` in any browser. That's it.

---

## Deploy free on GitHub Pages

1. Create a new GitHub repo (e.g. `my-portfolio`).
2. Upload **all** files in this folder (keep the folder structure).
3. Go to **Settings → Pages**.
4. Under "Build and deployment," set **Source = Deploy from a branch**, branch = `main`, folder = `/ (root)`. Save.
5. Wait ~1 minute. Your site is live at `https://YOUR-USERNAME.github.io/my-portfolio/`.

The included `.nojekyll` file makes sure every file is served correctly.

---

## How to customize (no coding required)

Open the `.html` files in any text editor and look for `<!-- EDIT -->` comments.

### Change the student name & branding
Search-and-replace **`Jane Doe`** and **`Jane`** across all files with the real name.

### Add your images (evidence)
1. Drop photos into `assets/images/` (e.g. `lab.jpg`).
2. In a subject page, change `src="../assets/images/placeholder.svg"` to `src="../assets/images/lab.jpg"`.
3. Update the `<strong>title</strong>` and caption text.

### Add your files (PDFs, slides, spreadsheets, code)
1. Drop files into `assets/files/` (e.g. `report.pdf`).
2. In a subject page, change the file link's `href="../assets/files/sample.pdf"` to your file.
3. Update the `ext` label (PDF / DOCX / XLSX / SLIDES / ZIP) and the title.

### Write reflections
Edit the text inside the `<div class="reflection">` block — explain how the subject made you college-ready, career-ready, or a better global citizen.

### Change colors per subject
Each subject page has `<body data-subject="...">`. Options: `math`, `science`, `english`, `social`, `tech`. Edit the color values at the top of `assets/style.css` to rebrand everything at once.

---

## File structure
```
portfolio/
├─ index.html              ← home page with subject menu
├─ .nojekyll               ← required for GitHub Pages
├─ assets/
│  ├─ style.css            ← all styling + colors (edit here to rebrand)
│  ├─ images/              ← put evidence photos here
│  └─ files/               ← put PDFs / docs / slides here
└─ subjects/
   ├─ math.html
   ├─ science.html
   ├─ english.html
   ├─ social-studies.html
   └─ tech.html
```

Each subject page has the same three sections — **Evidence & Documentation**, **Files & Documents**, and **Reflection** — so students just fill in the blanks.
