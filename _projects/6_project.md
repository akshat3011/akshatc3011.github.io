---
layout: page
title: Intelligent Document Summarizer
description: ml, nlp, algorithms
img: assets/img/doc_summarization.png
importance: 7
category: work
---

---
A Document Summarizer is a tool which for a given input text file
generates a output containing a list of sentences which better describes
our original file. We began with eliminating unimportant words (such
as stop words and punctuation ). We then calculate the term frequency
of every important word (\{words\}\textbackslash{}\{unimportant words\}),
and vectorize our sentences. We then cluster similar sentences together.
In the process, we ignore the sentences which have nearly zero or
near complete similarity. This is done to not let outliers affect
our clustering. We then choose the sentences that describe the cluster
best. An ordered collection of these sentences will be our summary
of the input file

More information  can be found here:
<ul>
  <li><a href="https://bitbucket.org/akshat3011/document_summarizer/src/master/">Project Report</a></li>
</ul>
