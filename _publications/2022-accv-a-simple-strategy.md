---
title: "A Simple Strategy to Make Neural Networks Provably Invariant"
collection: preprints
permalink: /publication/2022-accv-a-simple-strategy
date: 2022-10-04
venue: 'Asian Conference on Computer Vision (ACCV) (Accepted)'
authors: '<b>Kanchana Vaishnavi Gandikota</b>, Jonas Geiping, Zorah Lähner, Adam Czapliński, Michael Moeller'
teaser: /previews/gandikota2021trainingorarchitecture.png
paperurl: 'http://KCGandikota.github.io/files/pdfs/gandikota2022orbit.pdf'
arxiv: 'https://arxiv.org/abs/2106.10044'
categories: [Robustness]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/trainingorarchitecture.png" alt="Teaser Image" title="teaser" />

## Abstract

> Many applications require the robustness, or ideally the invariance, of a neural network to certain transformations of input data. Most commonly, this requirement is addressed by either augmenting the training data, using adversarial training, or defining network architectures that include the desired invariance automatically. Unfortunately, the latter often relies on the ability to enlist all possible transformations, which make such approaches largely infeasible for infinite sets of transformations, such as arbitrary rotations or scaling. In this work, we propose a method for provably invariant network architectures with respect to group actions by choosing one element from a (possibly continuous) orbit based on a fixed criterion. In a nutshell, we intend to 'undo' any possible transformation before feeding the data into the actual network. We analyze properties of such approaches, extend them to equivariant networks, and demonstrate their advantages in terms of robustness as well as computational efficiency in several numerical examples. In particular, we investigate the robustness with respect to rotations of images (which can possibly hold up to discretization artifacts only) as well as the provable rotational and scaling invariance of 3D point cloud classification.


## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @article{gandikota2021invariance,
        author 	= { {Kanchana Vaishnavi} Gandikota and Jonas Geiping and Zorah L\"ahner and Adam Czapli\'nski and Michael Moeller},
        title 	= {A Simple Strategy to Make Neural Networks Provably Invariant},
        booktitle   = {Asian Conference on Computer Vision (ACCV)},
        year 	= 2022,
    }
