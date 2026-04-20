# Offline-PDF-Merge
Offline HTML tool to merge two or more PDFs.

# How to use:

Put files in the same folder or drag and drop. Open index.html in a browser to merge.

```
index.html
pdf-lib.min.js
```

# What does it do?

- Drop in multiple PDFs or click to browse
- Drag them into whatever order you want
- Optionaly trim each selected PDF to a portion of its total pages
- Set a name for the final merged file
- Click **Merge** and the file will export/download



If you want to update it:

```sh
curl -o pdf-lib.min.js https://unpkg.com/pdf-lib/dist/pdf-lib.min.js
```

## Things to know

- Needs at least 2 files to merge
- Page ranges are inclusive `pp 2 – 5` gives you pages 2, 3, 4, and 5
- Encrypted PDFs load but encryption is ignored, the output will not be encrypted
- Tested in Chrome and Firefox
