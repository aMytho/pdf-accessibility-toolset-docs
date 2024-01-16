---
weight: 999
title: "Attribute Modifier"
description: ""
icon: "article"
date: "2024-01-05T18:24:17-06:00"
lastmod: "2024-01-05T18:24:17-06:00"
draft: false
toc: true
---

This tool allows for mass attribute modification. You can add, edit, or remove an attribute. This tool supports the ID, Title, and Actual/Alt text attributes.

Adding will add the attribute if it doesn't exist. Editing will modify the attribute regardless of if it exists. Deletion will remove the attribute. For most attributes, this will result in a blank string.

## Parameters

| Parameter          | Purpose                                                                       |
|--------------------|-------------------------------------------------------------------------------|
| Attribute          | The attribute to modify.                                                     |
| Action             | Add, edit, or remove a tag.                                                  |
| Value *(optional)* | If in add or edit mode, this will be the value of the attribute. If an attribute is being removed, this property is not used. |

## Output

Output of setting every image to have an alt text of "Our Logo".

![Modified image tags. Each tag has a new alt text value.](/img/attributeExample.png)