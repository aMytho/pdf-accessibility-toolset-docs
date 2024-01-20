---
weight: 403
title: "Insertion"
description: ""
icon: "article"
date: "2024-01-05T18:34:51-06:00"
lastmod: "2024-01-05T18:34:51-06:00"
draft: false
toc: true
---

Many tools insert tags into the document. If your tools does that, you will need to choose an insertion point. The below points are available:

- Before Selection: Finds the selection, and then inserts above (before) the tag. This is an adjacent position.
- After Selection: Finds the selection, and then inserts below (after) the tag. This is an adjacent position.
- First Child: Insertion will be the first element in the target selection.
- Last Child: Insertion will be the last element in the target selection.

You can only insert a tag in a valid position. For example, using the before/after insertion on the document root will not work.

If your tool does not insert a tag, you can ignore this part of the selection interface. In a future version this part will be hidden in such cases.