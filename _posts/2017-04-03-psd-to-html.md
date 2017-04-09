---
layout: post
title: PSD to HTML converter
categories:
- python
---

# PSD to HTML converter

[PSD to HTML converter](https://github.com/kirkins/psd2html) is a command-line python script which takes a psd as input and creates a
static website structure.

For example the following command:

    python psd.py -f my_photoshop.psd

Would create a folder containing all the photoshop layers as seperate images. The folder will also contain css file which records x, y
positions and an html file with an element for each layer.
