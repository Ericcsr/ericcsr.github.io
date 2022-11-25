---
title: "CEP3: Community Event Prediction with Neural Point Process on Graph"
collection: publications
permalink: /publication/cep3
excerpt: 'Jointly predicting event type as well as event time on continuous dynamic graph of community.'
date: 2022-11-24
venue: 'Learning on Graph 2022'
paperurl: 'https://openreview.net/forum?id=sfc0rjCBqS_'
citation: 'X. Wang,S. Chen, Y. He, M. Wang, Q. Gan, J. Yan, Y. Yang. (2022). &quot;CEP3: Community Event Prediction with Neural Point Process on Graph. &quot; <i>LoG 2022</i>.'
---
### Abstract
Many real world applications can be formulated as event forecasting on Continuous Time Dynamic Graphs (CTDGs) where the occurrence of a timed event between two entities is represented as an edge along with its occurrence timestamp. However, many previous works handle the problem in compromised settings, either formulating it as a link prediction task on the graph given the event time, or a time prediction problem for  event will happen next. In this paper, we propose a novel model combining Graph Neural Networks and Marked Temporal Point Process (MTPP) that jointly forecasts multiple link events and their timestamps on communities over a CTDG. Moreover, to scale our model to large graphs, we factorize the jointly event prediction problem into three easier conditional probability modeling problems. To evaluate the effectiveness of our model and the rationale behind such a decomposition, we establish a set of benchmarks and evaluation metrics.  The experimental results demonstrate the superiority of our model in terms of both accuracy and training efficiency. All the source codes and datasets are available at an anonymous repository and will be made publicly available.


![Visualization of link forecasting](/images/CEP3.png)
[Download paper here](https://openreview.net/forum?id=sfc0rjCBqS_)