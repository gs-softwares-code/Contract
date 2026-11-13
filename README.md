# GS-Softwares Agreement Studio

A browser-based website development agreement generator from GS-Softwares. Edit client and project details in a form, preview the agreement as an A4 document, and print it or save it as a PDF.

## Features

- Live agreement preview with editable client, date, scope, and timeline fields
- Default website-development agreement and Annexure A scope sheet
- A4 print layout with optional border and print-friendly pagination
- Zoom controls and optional highlights for fields that need attention
- Automatic saving of form values in the browser's local storage
- Responsive layout for desktop and mobile

## Run the app

This is a static, single-file web app; no build step or package installation is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser. For local server preview, run `python -m http.server 8000` from the repository directory and visit `http://localhost:8000`.
3. Fill in the document fields. Use **Use Today's Date** to populate the agreement date.
4. Select **Print / Save PDF** and choose **Save as PDF** in the browser's print dialog.

The app loads Tailwind CSS, Lucide icons, and fonts from third-party CDNs, so an internet connection is needed for those assets. Printing and PDF output use the browser's print functionality.

## Data and privacy

Form values are saved in the current browser using local storage under `gs_softwares_agreement_v1`. They are not submitted to a server by this app. Use **Reset** to clear the saved values and restore the template defaults. Avoid using a shared browser profile for confidential client information.

## Important

This project provides a document-generation template, not legal advice. Review and adapt the agreement to the transaction and applicable law, and consult a qualified legal professional before relying on it. Check all names, contact details, amounts, dates, and terms before signing or sharing a generated document.

## License

No license is currently specified in this repository. Contact the repository owner before redistributing or reusing the code.
