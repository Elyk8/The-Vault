# PDFs Attachments
```dataviewjs
const pdfFiles = app.vault.getFiles().filter(file => file.extension === "pdf" && file.path.includes("assets"))
dv.list(pdfFiles.map(file => dv.fileLink(file.path)))
```
# Image Attachments
```dataviewjs
const pdfFiles = app.vault.getFiles().filter(file => file.extension === "jpeg" && file.path.includes("assets/attachments"))
dv.list(pdfFiles.map(file => dv.fileLink(file.path)))
```