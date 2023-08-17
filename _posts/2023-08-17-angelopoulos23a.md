---
title: "Recommendation Systems with Distribution-Free\r Reliability Guarantees"
abstract: "When building recommendation systems, we seek to\r output a helpful set
  of items to the user. Under the\r hood, a ranking model predicts which of two\r
  candidate items is better, and we must distill these\r pairwise comparisons into
  the user-facing\r output. However, a learned ranking model is never\r perfect, so
  taking its predictions at face value\r gives no guarantee that the user-facing output
  is\r reliable. Building from a pre-trained ranking model,\r we show how to return
  a set of items that is\r rigorously guaranteed to contain mostly good\r items. Our
  procedure endows any ranking model with\r rigorous \fnite-sample control of the
  false\r discovery rate (FDR), regardless of the (unknown)\r data distribution. Moreover,
  our calibration\r algorithm enables the easy and principled\r integration of multiple
  objectives in recommender\r systems. As an example, we show how to optimize for\r
  recommendation diversity subject to a user-speci\fed\r level of FDR control, circumventing
  the need to\r specify ad hoc weights of a diversity loss against\r an accuracy loss.
  Throughout, we focus on the\r problem of learning to rank a set of possible\r recommendations,
  evaluating our methods on the\r Yahoo! Learning to Rank and MSMarco datasets."
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: angelopoulos23a
month: 0
tex_title: "Recommendation Systems with Distribution-Free\r Reliability Guarantees"
firstpage: 175
lastpage: 193
page: 175-193
order: 175
cycles: false
bibtex_author: Angelopoulos, Anastasios N and Krauth, Karl and Bates, Stephen and
  Wang, Yixin and Jordan, Michael I
author:
- given: Anastasios N
  family: Angelopoulos
- given: Karl
  family: Krauth
- given: Stephen
  family: Bates
- given: Yixin
  family: Wang
- given: Michael I
  family: Jordan
date: 2023-08-17
address:
container-title: "Proceedings of the Twelfth Symposium on Conformal\r and Probabilistic
  Prediction with Applications"
volume: '204'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 8
  - 17
pdf: https://proceedings.mlr.press/v204/angelopoulos23a/angelopoulos23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
