---
title: Explanation of Link Predictions on Knowledge Graphs via Levelwise Filtering and Graph Summarization
authors:
- admin
- claudia
- Nicola Fanizzi
date: '2024-05-01'
publication_types: ['paper-conference']
publication: '*The Semantic Web: 21st International Conference, ESWC 2024, Hersonissos, Crete, Greece, May 26–30, 2024, Proceedings, Part I*'
doi: 10.1007/978-3-031-60626-7
abstract: Link Prediction methods aim at predicting missing facts in Knowledge Graphs (KGs) as they are inherently incomplete. Several methods rely on Knowledge Graph Embeddings, which are numerical representations of elements in the Knowledge Graph. Embeddings are effective and scalable for large KGs; however, they lack explainability. Kelpie is a recent and versatile framework that provides post-hoc explanations for predictions based on embeddings by revealing the facts that enabled them. Problems have been recognized, however, with filtering potential explanations and dealing with an overload of candidates. We aim at enhancing Kelpie by targeting three goals reducing the number of candidates, producing explanations at different levels of detail, and improving the effectiveness of the explanations. To accomplish them, we adopt a semantic similarity measure to enhance the filtering of potential explanations, and we focus on a condensed representation of the search space in the form of a quotient graph based on entity types. Three quotient formulations of different granularity are considered to reduce the risk of losing valuable information. We conduct a quantitative and qualitative experimental evaluation of the proposed solutions, using Kelpie as a baseline.
url_code: 'https://github.com/rbarile17/imagine'
featured: true
tags:
    - Knowledge Graphs
    - Explanation
---
