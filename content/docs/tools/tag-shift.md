---
weight: 306
title: "Tag Shift"
description: ""
icon: "article"
date: "2024-04-16T20:07:52-05:00"
lastmod: "2024-04-16T20:07:52-05:00"
draft: false
toc: true
---

This tool can help to remove nested tags that are the same element type. Many PDFs have tags that unnecessarily encapsulate another tag. For example, a paragraph tag may incorrectly have a child paragraph tag. This tool will automatically move the child tag up one level, leaving the parent intact. If you want to delete the parent tag if it is empty, use the Remove Empty Tag tool after this one.

## Parameters

The Tag Type must must match the selection for the child to be moved. The child element is the selection.

| Parameter | Purpose                                                                                                                                                            |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tag Type  | This is the type of tag that the toolset will search for. This is the *parent* element. If a child element is a direct child of this element, it will be moved up. |


## Output

Output showing the nested tags on the left and the corrected tags on the right. The extra tags were moved to the bottom of the tag root (which happened to be the next parent.)

![Duplicate nested tags were moved to the next parent at the end of the children list'](/img/tagShifterExample.jpg)