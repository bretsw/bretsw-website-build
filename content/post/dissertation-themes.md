+++
title = "Dissertation Themes"

date = 2020-07-09T00:00:00
lastmod = 2020-07-29T00:00:00
draft = false

tags = ["dissertation", "R", "dataviz", "heatmap", "msu"]
summary = ""

[header]
image = ""
caption = ""

[[gallery_item]]
album = ""
image = ""
caption = ""

[[gallery_item]]
album = ""
image = ""
caption = ""

[[gallery_item]]
album = ""
image = ""
caption = ""

# **Bold**
# *Italic*
# `Code`
# ~~strikethrough~~

# ```bash
# Code block
# ```
        
# [Hyperlink text](https://themes.gohugo.io/theme/academic/)
# {{< gallery >}}

# - Unordered list item 1
# - Unordered list item 2

# ## Header 2
# ### Header 3

# 1. Ordered list item 1
#    * Indented list item
# 2. Ordered list item 2

+++

As I've wrapped up numerous cycles of qualitative coding of interview data for my dissertation, *Into the edu-verse: New teachers’ agency in self-directed learning with social media*, I used `geom_tile()` in **{ggplot2}** to create heatmap plots to help me quickly visualize how thematic codes varied by interview participant and by modality.

## Codes by Participant

![Themes by participant](/img/dissertation-themes-heatmap-sorted2.png)

## Codes by Modality

![Themes by modality](/img/dissertation-modalities-heatmap-sorted2.png)

I've shared the code to produce these plots in a [GitHub repository](https://github.com/bretsw/dissertation-themes), and you can also [view on RPubs](https://rpubs.com/bretsw/dissertation-themes) a variety of different heatmaps I created en route to these final plots.
