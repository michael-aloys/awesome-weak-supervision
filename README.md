# awesome-weak-supervision

A curated list of weak and distant supervision papers and tools.

## Table of Contents
- [Introduction](#introduction)
- [Contributing](#contributing)
- [Surveys](#surveys)
- [Foundational Papers](#foundational-papers)
- [Libraries & Tools](#libraries-and-tools)
- [Datasets & Benchmarks](#datasets-and-benchmarks)

## Introduction

Weak supervision and distant supervision provide ways to (semi-) automatically generate training data for machine learning systems in a fast and efficient manner where normal, supervised training data is lacking. This idea is popular in fields like natural language processing and computer vision and is actively researched. Here, we list interesting papers and tools to help newcomers from both the research and the application side try out weak supervision.

This list was started by the organizers for the [WeaSuL Workshop on Weakly Supervised Learning](https://weasul.github.io/organizers/) at ICLR'21 and we welcome contributions to extend it.

## Contributing

If you want to contribute to this list, just create a pull-request or a new issue. For a paper or tool, please provide all the necessary information (authors, title, conference, link, topic tags, short description). If you are unsure, feel free to open an issue to discuss it. If you encounter any typos, just let us know. Thanks!

## Surveys

Surveys give a broad overview of a field and can allow you to quickly get insights into current trends and issues for future work.

- [Image Classification with Deep Learning in the Presence of Noisy Labels: A Survey](https://arxiv.org/abs/1912.05170) (Arxiv, 2021) [CV] A survey on how to handle the errors in weakly supervised or other noisily labeled data for computer vision.
- [A Survey on Recent Approaches for Natural Language Processing in Low-Resource Scenarios](https://arxiv.org/abs/2010.12309) (NAACL, 2021) [NLP] Section 4 covers both methods for weakly supervision in different NLP tasks as well as how to handly noisy labels.
- [A Brief Survey of Relation Extraction Based on Distant Supervision](https://link.springer.com/chapter/10.1007/978-3-030-22744-9_23) (ICCS, 2019) [NLP, RE] A survey specifically on distant supervision for relation extraction.
- [Relation Extraction Using Distant Supervision: A Survey](https://dl.acm.org/doi/10.1145/3241741) (ACM Computing Surveys, 2018) [NLP, RE] Another survey specifically on distant supervision for relation extraction.
- [A Survey of Noise Reduction Methods for Distant Supervision](https://dl.acm.org/doi/10.1145/2509558.2509571) (AKBC 2013) [NLP, RE] A survey that covers different ways to handle annotation errors in distantly supervised relation extraction data.

## Foundational Papers

Important steps in how we came to the current state of the art.

- [Distant Supervision for Relation Extraction Without Labeled Data](https://www.aclweb.org/anthology/P09-1113/) (ACL, 2009) [NLP, RE]
- [Data Programming: Creating Large Training Sets, Quickly](https://papers.nips.cc/paper/2016/hash/6709e8d64a5f47269ed5cea9f625f7ab-Abstract.html) (NIPS 2016) [ML]


## Libraries and Tools

Open-source libraries and tools already providing implementations that get you started quickly.

- [Cleanlab](https://github.com/cgnorthcutt/cleanlab) [ML, CV, NLP] "Python package for machine learning with noisy labels. cleanlab cleans labels and supports finding, quantifying, and learning with label errors in datasets."
- [Knodle](https://github.com/knodle/knodle) [ML, CV, NLP] "Modular weakly supervised learning with PyTorch."
- [Snorkel](https://github.com/snorkel-team/snorkel) [ML, CV, NLP] "Programmatically build and manage training data.”
- [ANEA](https://github.com/uds-lsv/anea) [NLP] "A tool to automatically annotate named entities in unlabeled text based on entity lists for the use as distant supervision"

## Datasets and Benchmarks

Datasets generated through weak and distant supervision. These works can provide both insights into how to generate weakly supervised data as well as to evaluate your learning algorithms on them.

- [NoisyNER. Analysing the Noise Model Error for Realistic Noisy Label Data](https://arxiv.org/abs/2101.09763) (AAAI, 2021) [NLP, NER] A named entity recognition dataset with different label sets created through distant supervision and manual rules. 
- [Learning from Rules Generalizing Labeled Exemplars](https://arxiv.org/abs/2004.06025) (ICLR, 2020) [ML, NLP] Four NLP datasets on text classification and slot filling.
- [Beyond Synthetic Noise: Deep Learning on Controlled Noisy Labels](http://proceedings.mlr.press/v119/jiang20c.html) (PMLR, 2020) [CV] A dataset with noisy labels obtained through web crawling.
- [Learning with Noisy Labels for Sentence-level Sentiment Classification](https://www.aclweb.org/anthology/D19-1655/) (EMNLP, 2019) [NLP, Sentiment] A sentiment analysis dataset created through weak supervision leveraging the context of sentences.
- [Food-101N. CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise](https://openaccess.thecvf.com/content_cvpr_2018/html/Lee_CleanNet_Transfer_Learning_CVPR_2018_paper.html) (CVPR, 2018) [CV] An image detection dataset focused on a specific domain.
- [Cross-lingual Name Tagging and Linking for 282 Languages](https://www.aclweb.org/anthology/P17-1178.pdf) (ACL, 2017) [NLP, NER, multilingual] A multilingual named entity recognition dataset derived from Wikipedia (WikiAnn). 
- [WebVision. WebVision Database: Visual Learning and Understanding from Web Data](https://data.vision.ee.ethz.ch/cvl/webvision//dataset2017.html) (Arxiv, 2017) [CV] An image detection dataset created through weak supervision from web crawling.
- [Clothing1M. Learning From Massive Noisy Labeled Data for Image Classification](https://ieeexplore.ieee.org/document/7298885) (CVPR, 2015) [CV] An image detection dataset that leverages the context of images for automatic labeling.
- [TinyImages. 80 Million Tiny Images: A Large Data Set for Nonparametric Object and Scene Recognition](https://dl.acm.org/doi/10.1109/TPAMI.2008.128) (TPAMI, 2008) [CV] Large image detection dataset.

