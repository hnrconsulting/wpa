HNR Consulting — PDF local/offline

1. jspdf.umd.min.js and qrcode.min.js are stored in the repository root.
2. index.html loads them with relative local paths only; no CDN is needed for PDF/QR generation.
3. Registration and translation quote PDFs are generated in the browser and downloaded as Blob files.
4. The “Ajouter un autre document” button is unrestricted: each click creates a new Nature / Nombre de pages pair.
5. Final PDF validation still requires every document row to be complete and tariff-recognizable.
6. Montserrat is embedded in index.html and registered in jsPDF for quote PDFs.
