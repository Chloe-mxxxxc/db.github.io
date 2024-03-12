---
layout: default
title: Dongba Hieroglyphics Dataset
description: This dataset provides historical Dongba manuscript data, collected from the Naxi Yuan Ke Dongba Ancient Books Translation and Annotation.
---

## Introduction
In the realm of historical manuscript research, scholars have devoted immeasurable hours to the meticulous identification and documentation of symbols within ancient texts.

Although much of the prior research in computer vision has prioritized few-shot/one-shot/open-set object detection, there's an omission in studies centered on the detection of unseen texts. 

![](/docs/7.png)

*Fig 1. Manuscript notes of a historian studying Dongba texts: newly discovered characters categorized and annotated*

Consequently, we introduce this aspect in this section. The current methodology, vital for comprehending historical and cultural evolution, is predominantly manual and labor-intensive. 

Constrained by resources, researchers manually decipher new symbols, carefully record their observations, and then systematically catalog these symbols. 

Figure 1 exemplifies the arduous process a scholar undergoes when documenting insights from Dongba manuscripts ( 'Dongba Hieroglyphics', one of the ancient hieroglyphic scripts affiliated with China, was invented by the ancestors of the Naxi minority in China ).  

While comprehensive, this approach is prone to inefficiencies, potential misinterpretations, and inaccuracies due to human factors. 

![](/docs/11.jpg)
*Fig 2. Data example in the DBH dataset, sourced from the Naxi Yuan Ke Dongba Ancient Books Translation and Annotation, ISBN 978-7-5367-8040-8*

As the total number of distinct Dongba characters is unknown, text spotting in manuscripts is an open-set problem, where spotting novel characters helps decipher historical texts. We collected data from Dongba sutras, annotating and summarizing it into a dataset of 3633 bounding boxes across 253 categories. To accommodate one-shot tasks, experts hand-wrote an additional 253 characters, using them as support images. Figure 2 provides an example of the DBH dataset.

This dataset is available for download at  [Link](https://github.com/infinite-hwb/ots/tree/master/DATA/DBH%20dataset).

[back](./)

