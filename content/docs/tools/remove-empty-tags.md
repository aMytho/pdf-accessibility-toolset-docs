---
weight: 308
title: "Remove Empty Tags"
description: ""
icon: "article"
date: "2024-04-16T20:46:22-05:00"
lastmod: "2024-04-16T20:46:22-05:00"
draft: false
toc: true
---

This tool will remove any empty tags. This works in the same manner that the Above tool does. Note that you may need to run this tool several times if you have nested empty tags.

This is commonly used with the [All Tags](/docs/selection/all-tags) selection.

## Parameters

This tool has no parameters. 

## Output

Output showing that the empty tags were removed. After this tool was run, there were previously non-empty tags that are **now** empty. The remaining empty tags were **not** removed. This is because they were not empty when the tool checked for them. If you have an empty tag in an tag with no elements beside the empty tag, only the lowest child will be removed. You can run the tool multiple times to remove them all, or adjust your selection.

Based on the order of the "All Tags" selection, the lowest Sect and last 2 Divs were removed.

![The empty Div tag is removed after this tool is used..'](/img/emptyTagRemoverExample.jpg)