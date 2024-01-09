---
weight: 999
title: "Table Generator"
description: ""
icon: "article"
date: "2024-01-05T18:16:56-06:00"
lastmod: "2024-01-05T18:16:56-06:00"
draft: true
toc: true
---


This tool lets you create a table with all the required elements. You must enter the amount of rows and columns that you want generated. The first row will automatically contain header cells. You can optionally enter a title.

Since this is just a tagging operation, you will still need to assign content to the table in a PDF editor.

## Parameters

| Parameter       | Purpose                                                            |
|-----------------|--------------------------------------------------------------------|
| Title *(Optional)* | The title of the parent Table tag. Used by the remediator for identification. |
| Column Amount   | The amount of columns to generate. This determines the amount of Table Data Cells (TD) per row. |
| Row Amount      | The amount of rows to generate.                                     |

## Output

Output with a title of "Example", 20 rows, and 4 columns.

![Generated table. Contains a parent table tag and twenty rows each with 4 columns. The first row contains header cells. The title is 'example title'](/img/tableExample.png)