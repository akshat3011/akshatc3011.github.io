---
layout: page
title: Expert Paper Reccomendation System
description: Keywords - machine learning, nlp, clustering, algorithms
img: assets/img/exp-rec-system.jpeg
importance: 6
category: work
---
In a medium-to-large scale conference, there are thousands of research papers submitted, with only a limited number of reviewers for these papers in this regard. One of the problems that needs attention in such research conferences is that of assigning any submitted paper to be reviewed by an expert on the basis of their expertise in the field of which the paper belongs. It is manually nearly impossible to go through each paper and find a suitable expert in the field to review it, considering we will be needing not only the category the paper belongs to but also the expertise field of the expert based on the papers they have written in the past. This is where automation comes into play and the need for an automatic paper-reviewer assignment system becomes imperative.

In this paper, we put forth two algorithms for the same. The first algorithm assigns the experts who have a paper in closest distance to given paper. The second algorithm is a hybrid of content-based filtering and collaborative filtering. We cluster all the papers (including those of the experts) and for each cluster, each expert has an overall rating which describes the expert's expertise in that cluster. And then the semi-supervised clustering algorithm assigns papers that we have to recommend to the experts which have high expertise in that cluster.

More information can be found here:
<ul>
  <li><a href="https://bitbucket.org/akshat3011/recommendation-system/src/master/">Project Bitbucket Link </a></li>
</ul>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/epr-design.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Class Diagram for design of expert-paper reccomendation system
</div>
