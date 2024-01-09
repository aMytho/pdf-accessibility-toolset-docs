---
weight: 999
title: "Tag Generator"
description: ""
icon: "article"
date: "2024-01-05T18:20:05-06:00"
lastmod: "2024-01-05T18:20:05-06:00"
draft: true
toc: true
---

This tool lets you create any tag dynamically. Simply enter the type of tag that you want and the amount. The tag(s) will be generated when the task is ran. Unlike the List/Table generators, this Task only generates the specified tag. Generating a List will not generate the required LI, Lbls, and LBody tags. If you need the full structure consider using those other tools instead.

Since this is just a tagging operation, you will still need to assign content to the tag in a PDF editor.

## Parameters

| Parameter       | Purpose                                                                                          |
|-----------------|--------------------------------------------------------------------------------------------------|
| Group Title *(Optional)* | If a title is chosen, a parent Div tag will be generated. All the tags will be contained within that parent. Used by the remediator for identification. |
| Tag Amount      | The amount of tags to generate.                                                                   |
| Tag Type        | The type of tag to generate. You can generate *any* tag, but you are responsible for making sure that the structure conforms to accessibility requirements. |


## Output

Output with a group title of "Example" and 5 H6 tags.

![Generated structure. There is a parent Div with 5 header 6 elements as the children. The title is 'example title'](/img/tagExample.png)