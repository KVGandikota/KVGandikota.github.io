---
title: "Blind Single Image Reflection Suppression for Face Images using Deep Generative Priors"
collection: publications
permalink: /publication/2019-iccvw-Blind-Single-Image-Reflection-Suppression-for-Face-Images-using-Deep-Generative-Priors
date: 2019-10-27
venue: 'IEEE/CVF International Conference on Computer Vision Workshops'
paperurl: 'http://KVGandikota.github.io/files/pdfs/face_reflection_removal_iccvw.pdf'
authors: 'Paramanand Chandramouli, <b>Kanchana Vaishnavi Gandikota</b>'
teaser: /previews/face_reflection.png
categories: [Image-Restoration]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/face_reflection.png" alt="Teaser Image" title="teaser" />

## Abstract

> The goal of single image reflection removal is to suppress unwanted merging of radiances from different surfaces in the scene. This is an inherently ill-posed and challenging problem. Conventional approaches use different assumptions and constraints on the background and reflected layers to solve this problem. Recently, deep learning-based approaches have been applied to this task. These methods require extensive amount of realistic data for training. In this paper, we propose to incorporate class-specific prior models for reducing the ill-posedness of the reflection separation task. Specifically, we use a pre-trained deep face-generative model for reflection supression from face images. We design an optimization scheme that effectively leverages the deep generative model and leads to a constrained solution space. Our method does not require training data corresponding to reflection separation task. We evaluate our proposed approach using both synthetic and real world facial images containing reflections and compare with existing state-of-the-art techniques. The results demonstrate advantages of our approach over the current state-of-the-art in single image reflection separation from faces.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

@inproceedings{chandramouli2019blind,
  title={Blind single image reflection suppression for face images using deep generative priors},
  author={Chandramouli, Paramanand and Vaishnavi Gandikota, Kanchana},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision Workshops},
  year={2019}
}


