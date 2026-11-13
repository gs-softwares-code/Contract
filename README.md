<div align="center">
  <img src="favicon.svg" alt="GS-Softwares Agreement Studio icon" width="88" height="88">
  <h1>GS-Softwares Agreement Studio</h1>
  <p><strong>Create, customize, preview, and print website development agreements.</strong></p>
  <p>
    <a href="https://github.com/gs-softwares-code/Contract"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub repository"></a>
    <img src="https://img.shields.io/badge/HTML5-Static%20Web%20App-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 static web app">
    <img src="https://img.shields.io/badge/No%20Build%20Required-Ready%20to%20Run-16a34a?style=for-the-badge&logo=checkmarx&logoColor=white" alt="No build required">
  </p>
</div>

---

##  Overview

Agreement Studio is a lightweight, browser-based tool for preparing a website development agreement. Update client and project details in the editor and see them reflected immediately in an A4 document preview. Print the agreement or save it as a PDF from your browser.

##  Features

- **Live editing:** Update agreement date, client details, demo URL, scope limits, timelines, revision rounds, and support terms.
- **Complete template:** Includes the website development agreement, signature blocks, and an Annexure A scope sheet.
- **Print-ready output:** A4 page styling, print pagination, optional document border, and browser print/PDF export.
- **Convenient preview:** Zoom controls, editable-field highlights, and responsive controls for mobile screens.
- **Automatic local saving:** Form entries persist in the browser's local storage between visits.
- **No build pipeline:** A single HTML file; no package manager or compilation step needed.

##  Built with

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Lucide-Icons-F56565?style=flat-square" alt="Lucide icons">
</p>

The page loads Tailwind CSS, Lucide icons, and Google Fonts from third-party CDNs. An internet connection is required for these visual assets; the browser's native print feature handles PDF generation.

##  Getting started

### Open locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. Fill in the agreement fields and review the generated document.
4. Select **Print / Save PDF**, then choose **Save as PDF** in the print dialog.

### Serve locally (optional)

From the repository directory, run:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

##  Using the editor

1. Enter the agreement date manually or select **Use Today's Date**.
2. Complete the client details and add the approved demo/reference URL.
3. Adjust scope limits and timeline or support values as needed.
4. Review the preview for empty highlighted fields, then print or save as PDF.
5. Use **Reset** to clear saved entries and restore the template defaults.

##  Privacy

The app stores form values only in the browser's local storage, using the key `gs_softwares_agreement_v1`. It does not submit form data to a backend. On shared devices, clear the stored data after use and avoid entering confidential information.

##  Legal notice

This application is a document template and is **not legal advice**. The included agreement contains preset terms and amounts. Review and adapt the document for each transaction and applicable law, and seek advice from a qualified legal professional before signing or relying on it.

##  App icon

The repository favicon is [`favicon.svg`](favicon.svg). The app also defines its browser-tab icon inline in `index.html`.

## 📄 License

No license is currently specified. All rights are reserved by default; contact the repository owner before redistributing or reusing this project.
