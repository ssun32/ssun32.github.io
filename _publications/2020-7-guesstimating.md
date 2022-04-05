---
title: "CLIReval: Evaluating Machine Translation as a Cross-Lingual Information Retrieval Task"
collection: publications
excerpt: 'We present CLIReval, an easy-to-use toolkit for evaluating machine translation (MT) with the proxy task of cross-lingual information retrieval (CLIR). Contrary to what the project name might suggest, CLIReval does not actually require any annotated CLIR dataset. Instead, it automatically transforms translations and references used in MT evaluations into a synthetic CLIR dataset; it then sets up a standard search engine (Elasticsearch) and computes various information retrieval metrics (eg, mean average precision) by treating the translations as documents to be retrieved. The idea is to gauge the quality of MT by its impact on the document translation approach to CLIR. As a case study, we run CLIReval on the “metrics shared task” of WMT2019; while this extrinsic metric is not intended to replace popular intrinsic metrics such as BLEU, results suggest CLIReval is competitive in many language pairs in terms of correlation to human judgments of quality. CLIReval is publicly available at https://github. com/ssun32/CLIReval.'
date: 2020/07
venue: '58th Annual Meeting of the Association for Computational Linguistics: System Demonstrations (2020)'
paperurl: 'https://aclanthology.org/2020.acl-demos.18.pdf'
---


