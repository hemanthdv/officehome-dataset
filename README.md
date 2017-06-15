<!---
---
layout: post
title: Office-Home Dataset
description: "Object Recognition dataset for domain adaptation experiments"
comments: false
---
-->

# Office-Home Dataset
The Office-Home dataset has been created to evaluate domain adaptation algorithms for object recognition using deep learning. It consists of images from 4 different domains: Artistic images, Clip Art, Product images and Real-World images. For each domain, the dataset contains images of 65 object categories found typically in Office and Home settings.

## Data Collection
The images in the dataset were collected using a python web-crawler that crawled through several search engines and online image directories. This initial run searched for around 120 different objects and produced over 100,000 images across the different categories and domains. These images were then filtered to ensure that the desired object was in the picture. Categories were also filtered to make sure that each category had at least a certain number of images. The latest version of the dataset contains around 15,500 images from 65 different categories.

| Domain     | Min: # |Max: Size              |  Acc.         |
| :--------- |:------:|:---------------------:|:-------------:|
| Art        | 15     | 4384$\times$2686 pix. |44.99$\pm$1.85 |
| Clipart    | 39     | 2400$\times$2400 pix. |53.95$\pm$1.45 |
| Product    | 38     | 2560$\times$2560 pix. |66.41$\pm$1.18 |
| Real-World | 23     | 6500$\times$4900 pix. |59.70$\pm$1.04 |
