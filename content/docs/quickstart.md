---
weight: 800
title: "Quickstart"
description: ""
icon: "article"
date: "2024-01-05T18:44:23-06:00"
lastmod: "2024-01-05T18:44:23-06:00"
draft: false
toc: true
---

Welcome to the docs! These pages contain all of the info related to the project.

{{< alert context="success" text="The live project can be found on [our website](https://pdf-accessibility.tools)." />}}

## Purpose

The Pdf Acc (Accessibility) Toolset is a utility for making PDFs accessible. It has a variety of tools to assist in the remediation process. Most of them deal with the tag tree. Since many operations are repetitive by nature, they are easily automated. The toolset can also help in setting basic PDF metadata. These features will expand over time to cover more parts of the accessibility process.

Feature requests can be made on the [issues page](https://github.com/amytho/pdf-acc-toolset). Alternatively, you can fork the project and add the feature yourself. The codebase is well documented and the existing tool and selection systems are easy to hook into.

### Tech Stack

The Toolset is a .NET Blazor WASM (Web Assembly) application. The UI is in HTML and CSS, while the logic is in C#. It is compiled into Web Assembly to run in the browser. All processing is done locally. PDF modification is done with the iText library.

The [source code](https://github.com/aMytho/Pdf-Acc-Toolset) is freely available. Developers are encouraged to contribute if they have a feature they want added.

### License

The Toolset is under the AGPLv3 license.

#### iText

iText is distributed under the AGLPLv3 license as it uses the community edition. This project (Pdf Toolset) does not modify the iText software in any way. Their license can be seen on the [license](https://itextpdf.com/how-buy/legal/agpl-gnu-affero-general-public-license) page.
