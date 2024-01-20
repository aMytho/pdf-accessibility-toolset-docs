---
weight: 201
title: "Import"
description: "Learn about supported PDF versions and the import options."
icon: "article"
date: "2024-01-05T19:23:17-06:00"
lastmod: "2024-01-05T19:23:17-06:00"
draft: false
toc: true
---

The toolset is built with the iText library. As a result, it *should* accept any PDF version. However, it works best with PDFs that are version 1.7 or greater.

## Import Settings

The below options can be customized when importing a PDF:
- Filename: The **exported** filename of your PDF.
- Title: The document title. This is displayed in most PDF viewers in place of the filepath.
- Language: The document language.
- Standard: Allows you to set the UA ([Universal Accessibility](https://pdfa.org/resource/pdfua-in-a-nutshell/)) standard.

## Import Existing / Save Changes

While importing, you can choose to use the existing values or save changes. Using the existing values will not make any changes to the PDF, even if you modified one of the import properties. Save Changes will use whatever is shown in the import settings box.

## Password Protected Documents

Some documents come with a password. If the toolset fails to open a document, it will ask for a password. The toolset will require both read (user) and edit (owner) access.

Older versions of the PDF spec have a password protection strategy that is "Ask Nicely". This method of security is very poor and should not be used. The toolset will respect this password, but you should upgrade from it at the earliest opportunity. 

Passwords can be removed from the document via Acrobat or other *special* means. Exporting the document with the toolset will retain the password.