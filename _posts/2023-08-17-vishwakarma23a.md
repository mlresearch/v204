---
title: "Enterprise Disk Drive Scrubbing Based on Mondrian\r Conformal Predictors"
abstract: "Disk scrubbing is a process aimed at resolving read\r errors on disks by
  reading data from the\r disk. However, scrubbing the entire storage array at\r once
  can adversely impact system performance,\r particularly during periods of high input/output\r
  operations. Additionally, the continuous reading of\r data from disks when scrubbing
  can result in wear\r and tear, especially on larger capacity disks, due\r to the
  significant time and energy consumption\r involved. To address these issues, we
  propose a\r selective disk scrubbing method that enhances the\r overall reliability
  and power efficiency in data\r centers. Our method employs a Machine Learning model\r
  based on Mondrian Conformal prediction to identify\r specific disks for scrubbing,
  by proactively\r predicting the health status of each disk in the\r storage pool,
  forecasting n-days in advance, and\r using an open-source dataset. For disks predicted
  as\r non-healthy, we mark them for replacement without\r further action. For healthy
  drives, we create a set\r and quantify their relative health across the entire\r
  storage pool based on the predictor’s\r confidence. This enables us to prioritize
  selective\r scrubbing for drives with established scrubbing\r frequency based on
  the scrub cycle. The method we\r propose provides an efficient and dependable\r
  solution for managing enterprise disk drives. By\r scrubbing just 22.7% of the total
  storage disks, we\r can achieve optimized energy consumption and reduce\r the carbon
  footprint of the data center. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vishwakarma23a
month: 0
tex_title: "Enterprise Disk Drive Scrubbing Based on Mondrian\r Conformal Predictors"
firstpage: 56
lastpage: 73
page: 56-73
order: 56
cycles: false
bibtex_author: Vishwakarma, Rahul and Hwang, Jinha and Messoudi, Soundouss and Hedayatipour,
  Ava
author:
- given: Rahul
  family: Vishwakarma
- given: Jinha
  family: Hwang
- given: Soundouss
  family: Messoudi
- given: Ava
  family: Hedayatipour
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
pdf: https://proceedings.mlr.press/v204/vishwakarma23a/vishwakarma23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
