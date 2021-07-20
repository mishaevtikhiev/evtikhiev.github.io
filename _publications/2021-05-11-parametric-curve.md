---
title: "Multi-Threshold Token-Based Code Clone Detection"
authors: '<i><b>Yaroslav Golubev</b>, Viktor Poletansky, Nikita Povarov, and Timofey Bryksin</i>'
collection: publications
permalink: /publication/2021-05-11-parametric-curve
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-05-11
venue: "Proceedings of the 28th IEEE International Conference onSoftware Analysis, Evolution and Reengineering <b>(SANER'21)</b>"
paperurl: 'https://arxiv.org/abs/2002.05204'
citation: 'Golubev, Y., Poletansky, V., Povarov, N., & Bryksin, T. (2021, March). Multi-Threshold Token-Based Code Clone Detection. In 2021 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER) (pp. 496-500). IEEE.'
---
In this paper, we propose a modification to bag-of-tokens based clone detection that allows detecting more clone 
pairs of greater diversity without losing precision by implementing a multi-threshold search, i.e. conducting the 
search several times, aimed at different groups of clones. To combat the increase in operation time that this approach 
brings about, we propose an optimization that allows to significantly decrease the overlap in detected clones between 
the searches.We evaluate the method for two different popular clone detection tools on two datasets of different sizes. 
The implementation of the technique allows to increase the number of detected clones by 40.5-56.6% for different 
datasets. BigCloneBench evaluation also shows that the recall of detecting Strongly Type-3 clones increases from 
37.5% to 59.6%.

[Download paper here](https://arxiv.org/pdf/2002.05204.pdf)

Recommended citation: Golubev, Y., Poletansky, V., Povarov, N., & Bryksin, T. (2021, March). Multi-Threshold Token-Based Code Clone Detection. In 2021 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER) (pp. 496-500). IEEE..