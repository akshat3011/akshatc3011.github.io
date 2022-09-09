---
layout: page
title: Persona and Emotion aware Diaglogue system
description: Keywords - nlp, affective computing, language models, hci
img: assets/img/persona-emo-ds.jpeg
importance: 2
category: work
---

Current open-domain chit-chat dialogue systems are not very consistent and engaging. Past works have shown that supplementing social agents with persona and the ability to express emotions has helped in making conversations more captivating, specific, and consistent. Persona-based and emotion-based dialogue systems have been explored independently but dialogue systems involving both have not been studied. In this project, we incorporate both persona and emotions in our dialogue agent. Firstly, we create a dataset having persona and emotion labels for the dialogue. Then using this dataset we fine-tune a large generative language model (GPT-2) to generate the next utterance in a dialogue based on the given persona and desired emotion. We evaluate our dataset and model automatically as well as using human evaluations. Finally, we present our qualitative observations, limitations of our work, and possible future directions to take this work forward.

More information  can be found here:
<ul>
  <li><a href="https://drive.google.com/file/d/1qvr8Tmi05ak2PmnF1E3yYQSOWlt12HQj/view?usp=sharing">Project Report</a></li>
</ul>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/emo-response.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sample response of dialogue system based on different emotions and their intensities
</div>
