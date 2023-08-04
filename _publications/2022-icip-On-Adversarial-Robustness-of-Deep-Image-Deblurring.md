---
title: "On Adversarial Robustness of Deep Image Deblurring"
collection: publications
permalink: /publication/2022-icip-On-Adversarial-Robustness-of-Deep-Image-Deblurring
date: 2022-10-16
venue: 'IEEE International Conference on Image Processing (ICIP)'
authors: '<b>Kanchana Vaishnavi Gandikota</b>, Paramanand Chandramouli, Michael Moeller'
teaser: /previews/adv_deblur.png
arxiv: 'https://arxiv.org/abs/2210.02502'
categories: [Robustness]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/adv_deblur.png" alt="Teaser Image" title="teaser" />

## Abstract

> Recent approaches employ deep learning-based solutions for the recovery of a sharp image from its blurry observation. This paper introduces adversarial attacks against deep learning-based image deblurring methods and evaluates the robustness of these neural networks to untargeted and targeted attacks. We demonstrate that imperceptible distortion can significantly degrade the performance of state-of-the-art deblurring networks, even producing drastically different content in the output, indicating the strong need to include adversarially robust training not only in classification but also for image recovery.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

   @inproceedings{gandikota2022adversarial,
  title={On Adversarial Robustness of Deep Image Deblurring},
  author={Gandikota, Kanchana Vaishnavi and Chandramouli, Paramanand and Moeller, Michael},
  booktitle={IEEE International Conference on Image Processing (ICIP)},
  pages={3161--3165},
  year={2022},
  organization={IEEE}
}

