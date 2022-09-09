---
layout: page
title: Analyzing Happy Moments
description: Keywords - data science, sentiment analysis, nlp
img: assets/img/happy-moments.png
importance: 4
category: work
---

To psychological researchers, happiness is life experience marked by a preponderance of positive emotion. Feelings of happiness and thoughts of satisfaction with life are two prime components of subjective well-being (SWB). Thus, understanding true source or reasons of happiness is an interesting and useful task. Understanding happiness is not straightforward, rather it highly depends on past experience of an individual, but there are some commonalities between happiness similar group can be extracted out. Understanding happiness will help us to build applications that makes people happy.  We are using HappyDB dataset, a corpus of 100,000 happy moments. The dataset contains answers to the queries that correlate happy moments with the past events i.e what made people happy in the past 24 hours or alternatively, past 3 months. HappyDB also contains information about demographic characteristics of the person such as age, marital status, nationality etc. In this project, we aim to complete following three tasks:

<ol>

<li> Analyzing happy Moments among people of different age groups, sex, nationality etc. and understanding their source of happiness. </li>

<li> Categorizing each happy moment into these listed categories using Seq2Seq model:
<ol>
  <ul>
    <li>Achievement</li>

    <li>Affection</li>

    <li>Bonding</li>

    <li>Enjoying the moment</li>

    <li>Exercise</li>

    <li>Leisure</li>

    <li>Nature</li>
</ul>
<li> Building a heuristics to score positivity or negativity of a sentence.</li>
</ol>
More information and code can be found here:
<ul>
  <li><a href="https://bitbucket.org/akshat3011/happy_nlp/src/master/">Bitbucket Project Link</a></li>
</ul>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/happy_nlp.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Word Cloud for frequent words in happy moments for mid-aged adults (25-45 years)
</div>
