---
weight: 999
title: "List Generator"
description: ""
icon: "article"
date: "2024-01-05T18:11:07-06:00"
lastmod: "2024-01-05T18:11:07-06:00"
draft: false
toc: true
---

This tool lets you create accessible lists with ease. Each list contains all of the tags needed for accessibility. Every list has a parent List tag, a specified amount of List Items, List Item Bodies (dependent on amount of list items), and Labels (optional, also dependent on amount of list items).

Since this is just a tagging operation, you will still need to assign content to the list in a PDF editor.

## Parameters

| Parameter       | Purpose                                                            |
|-----------------|--------------------------------------------------------------------|
| Title *(Optional)* | The title of the parent List tag. Used by the remediator for identification. |
| List Amount     | The amount of List Items to generate.                               |
| Add labels      | If selected, each List Item will contain a Label tag.               |


## Output

Output with a title of "Example", 20 list items, and labels.

![Generated list. Contains a parent list tag, twenty list items each with a label and a list item body. The title is 'example title'](/img/listExample.png)