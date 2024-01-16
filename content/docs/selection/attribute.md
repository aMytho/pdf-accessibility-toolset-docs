---
weight: 801
title: "Attribute"
description: ""
icon: "article"
date: "2024-01-05T18:30:43-06:00"
lastmod: "2024-01-05T18:30:43-06:00"
draft: false
toc: true
---

This selection allows you to target a tag with a specific attribute. You can use this to target a specific tag anywhere in the document. You can also target multiple tags with a given attribute.

You can choose any of the below attributes:

- Id: The ID of a tag. Only use an existing ID, do not add your own.
- Title: The easiest attribute to use. Give a tag a title in Acrobat or any other program and target it with this selection.
- Actual Text: Target a tag with the given actual text.
- Alt Text: Target a tag with the given alt text.

Title is the preferred attribute because most PDF programs display the title of the tag in the tree. This makes it easy to modify and see the result. You should remove the title when you are done.

![Tag tree showing the title of a tag](/img/titleExample.png)

This selection may have multiple targets. Use the [Limit Selection](/docs/selection/limit) feature accordingly.
