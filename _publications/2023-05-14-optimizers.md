---
title: "Judging Adam: Studying the Performance of Optimization Methods on ML4SE Tasks"
authors: '<i>Dmitry Pasechnyuk, Anton Prazdnichnykh, <b>Mikhail Evtikhiev</b>, and Timofey Bryksin</i>'
collection: publications
permalink: /publications/2023-05-14-optimizers
date: 2023-05-14
venue: "proceedings of <b>ICSE'23</b>"
level: 'A*'
pdf: 'https://arxiv.org/pdf/2303.03540.pdf'
counter_id: 'C3'
abstract: "<p><b>Abstract</b>. Solving a problem with a deep learning model
requires researchers to optimize the loss function with a certain
optimization method. The research community has developed
more than a hundred different optimizers, yet there is scarce
data on optimizer performance in various tasks. In particular,
none of the benchmarks test the performance of optimizers
on source code-related problems. However, existing benchmark
data indicates that certain optimizers may be more efficient
for particular domains. In this work, we test the performance
of various optimizers on deep learning models for source code
and find that the choice of an optimizer can have a significant
impact on the model quality, with up to two-fold score differences
between some of the relatively well-performing optimizers. We
also find that RAdam optimizer (and its modification with the
Lookahead envelope) is the best optimizer that almost always
performs well on the tasks we consider. Our findings show a
need for a more extensive study of the optimizers in code-related
tasks, and indicate that the ML4SE community should consider
using RAdam instead of Adam as the default optimizer for code-
related deep learning tasks.</p>"
---