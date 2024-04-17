---
weight: 307
title: "Tag Reparent"
description: ""
icon: "article"
date: "2024-04-16T20:24:30-05:00"
lastmod: "2024-04-16T20:24:30-05:00"
draft: false
toc: true
---

This tool can help to remove nested tags that are the same element type. **This is the same as the Tag-Shift tool, but this tool will move up the tag tree recursively until it finds a match.** Read the [Tag-Shifter](/docs/tools/tag-shift) documentation before using this tool.

## Parameters

The Tag Type must must match the selection for the child to be moved. The child element is the selection. This tool also has an option to automatically delete the parent tag if it is empty after the child has been moved.

| Parameter       | Purpose                                                                                                                                                            |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tag Type        | This is the type of tag that the toolset will search for. This is the *parent* element. If a child element is a distant child of this element, it will be moved up. |
| Delete if Empty | If the parent tag is empty after the child is moved, the parent tag will be deleted.                                                                               |


## Output

Output showing the nested tags on the left and the corrected tags on the right. This example moved the last P tag up to the section. The two Divs were not needed. While the original parent tag (2nd Div) was removed, the first Div was not. This is because the Tag Reparent Deletion only removes the original parent, not grandparent tags. If you want to remove empty tags that are not the direct parent, use the Empty Tag Remover tool.

![Duplicate nested tags were moved out of their parent.'](/img/tagReparentExample.jpg)