---
title: "Argumentative Structure Analysis for Domain Adaptation"
excerpt: "My Master's Thesis project where I created a novel annotated dataset of conversational arguments, engineered a graph-based representation, and benchmarked LLM performance for relation classification.<br/><img src='/images/arg_structure_visual.png'>"
collection: portfolio
date: 2025-12-15
---

This project was the focus of my Master's Independent Study, investigating how identifying and representing argumentative structures in conversation can enhance neural conversation models. Focusing on the `r/ChangeMyView` corpus, the goal was to create a foundational, high-quality dataset and a structured representation to inform future work in domain adaptation for dialogue systems.

### Key Contributions:

* **Manual Annotation & Dataset Creation:** I developed a detailed annotation scheme to classify the relationship between conversational replies as 'Attack', 'Support', or 'Neutral'. I personally conducted a manual annotation effort on over 500 utterance pairs, establishing a novel dataset that revealed a high prevalence of 'Attack' relations, which is characteristic of the `r/ChangeMyView` forum.

* **Graph Construction:** To capture the structural dynamics of the conversations, I converted the annotated data into a directed graph representation using Python and the `networkx` library. In this graph, utterances are nodes and the annotated 'Attack', 'Support', or 'Neutral' labels are attributes on the directed edges, explicitly modeling the argumentative flow.

* **LLM Benchmarking:** I conducted initial experiments using a Llama-3.2-1b model to establish a zero-shot classification baseline for this new task. The results showed a significant discrepancy compared to human annotations, with the model exhibiting a strong bias towards 'Support' or 'Neutral' predictions. This underscores the difficulty of the task and highlights the value of the new structured dataset for future model fine-tuning.

This work provides a critical foundation for integrating symbolic argumentative structure with neural models, such as Graph Neural Networks, to build more nuanced and context-aware conversational AI.

