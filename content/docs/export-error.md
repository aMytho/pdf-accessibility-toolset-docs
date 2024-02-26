---
weight: 501
title: "Fixing Export Errors"
description: ""
icon: "article"
date: "2024-02-25T18:36:07-06:00"
lastmod: "2024-02-25T18:36:07-06:00"
draft: false
toc: true
---

Some PDFs create an error during the import or export process. This is frequently due to partial document corruption or software that doesn't follow the PDF standard. While the Toolset should support every PDF version, it works best with PDFs that are 1.7 or greater.

## Potential Solutions

If you are having export errors try the below options:
- "Save Changes" during the import process. This overwrites some of the metadata which can help if it is corrupted.
- Convert the PDF to v1.7 or greater. This can be done in Acrobat via the File -> Save As -> Optimized PDF. Select the latest PDF/Acrobat version.
- Export the PDF to a non-PDF format. Convert the new file back into a PDF with modern software. This will require more work to make it accessible, but it should fix any corruption since it is a new document.
- Create a blank PDF in a modern version of Microsoft Word or LibreOffice Writer. Export to a PDF. Combine this new PDF with the old PDF. Save the file and then remove the new page. This will force a conversion to a newer version.