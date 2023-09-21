---
title: "Exploring Open Domain Image Super-Resolution through Text"
collection: publications
permalink: /publication/2023_text_SR
date: 2023-29-07
venue: 'ICML 2023 Workshop on Artificial Intelligence & Human-Computer Interaction'
paperurl: 'http://KVGandikota.github.io/files/pdfs/aihci_23.pdf'
authors: '<b>Kanchana Vaishnavi Gandikota</b>, Paramanand Chandramouli'
teaser: /previews/aihci.png
categories: [Image Recovery][Vision & Language]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/ct_local_attack.png" alt="Teaser Image" title="teaser" />

## Abstract

> Low dose computer tomography (CT) acquisition using reduced radiation or sparse angle measurements is recommended to decrease the harmful effects of X-ray radiation. Recent
works successfully apply deep networks to the problem of low dose CT recovery on benchmark datasets. However, their robustness needs a thorough evaluation before use in clinical
settings. In this work, we evaluate the robustness of different deep learning approaches and classical methods for CT recovery. We show that deep networks, including model
based networks encouraging data consistency are more susceptible to untargeted attacks. Surprisingly, we observe that data consistency is not heavily affected even for these poor
quality reconstructions, motivating the need for better regularization for the networks. We demonstrate the feasibility of universal attacks and study attack transferability across
different methods. We analyze robustness to attacks causing localized changes in clinically relevant regions. Both classical approaches and deep networks are affected by such attacks
leading to change in visual appearance of localized lesions, for extremely small perturbations. As the resulting reconstructions have high data consistency with original measurements,
these localized attacks can be used to explore the solution space of CT recovery problem.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

@misc{
gandikota2023exploring,
title={Exploring Open Domain Image Super-Resolution through Text},
author={Kanchana Vaishnavi Gandikota and Paramanand Chandramouli},
booktitle={ICML 2023 Workshop on Artificial Intelligence & Human-Computer Interaction},
year={2023},
url={[https://openreview.net/forum?id=L-N1uAxfQk1](https://github.com/helenavasc/AI_HCI_Workshop_ICML_2023/blob/c142ae4512c174ce5da5af05710051849c8b9ea9/papers/Exploring_Open_Domain.pdf)https://github.com/helenavasc/AI_HCI_Workshop_ICML_2023/blob/c142ae4512c174ce5da5af05710051849c8b9ea9/papers/Exploring_Open_Domain.pdf}
}
