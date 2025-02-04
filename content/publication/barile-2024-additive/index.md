---
title: Additive Counterfactuals for Explaining Link Predictions on Knowledge Graphs
authors:
- admin
- claudia
- Nicola Fanizzi
date: '2025-01-01'
publication_types: ['paper-conference']
publication: '*International Conference on Knowledge Engineering and Knowledge Management: 24th International Conference, EKAW 2024, Amsterdam, The Netherlands, November 26–28, 2024, Proceedings*'
doi: 10.1007/978-3-031-77792-9_21
abstract: The goal of Link Prediction is to predict missing facts in Knowledge Graphs that are inherently incomplete. Embedding models are generally adopted for this purpose since they are effective and scalable. However, they lack both interpretability and, more importantly, explainability, which is crucial in many tasks and domains. To fill this gap, post-hoc explanations are often computed. A post-hoc explanation for an embedding-based link prediction typically consists of discovering facts that made the prediction possible. Methods that can yield such explanations tend to provide subtractive counterfactual explanations, i.e., identify facts whose removal has the greatest impact on the predictions. However, since KGs are incomplete, there may be facts that are missing in the KG but useful for the explanations. Therefore, we formalize a new complementary approach based on the generation of plausible and meaningful additional facts to be used for providing explanations. Specifically, we propose Imagine, that can generate additive counterfactual explanations, by identifying the additional facts that most affect predictions. It builds on a post-training technique, which is used to assess the impact of adversarial modifications of the knowledge graph, and on Graph Summarization, that is used for identifying plausible additions. We present a comparative experimental study that proves the effectiveness of the proposed solution through quantitative and qualitative evaluations.
url_code: 'https://github.com/rbarile17/imagine'
featured: true
tags:
    - Knowledge Graphs
    - Explanation
---
