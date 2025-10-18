---
title: "Towards Explainable Food Hazard Detection"
excerpt: "A neuro-symbolic approach to food hazard detection that combines Large Language Models (Llama-3.1-8B) with knowledge graphs (ConceptNet) to create an inherently explainable classification system.<br/><img src='/images/food_hazard_visual.png'>"
collection: portfolio
date: 2024-12-14
---

As food systems grow more complex, ensuring food safety with transparent and interpretable AI is critical. This project introduces a novel neuro-symbolic approach for food hazard detection that prioritizes explainability without sacrificing performance, especially in low-data scenarios.

### Key Contributions:

* **Neuro-Symbolic Architecture:** I co-developed a system that uses CoCo-Ex to extract key concepts from food recall notices and maps them to the ConceptNet knowledge graph. A Llama-3.1-8B-Instruct model was then used to filter and refine these concepts, creating a context-specific sub-graph.
* **Explainable Classification:** By leveraging the relationships and distances between concepts within the constructed knowledge graph, the system can classify hazards in a way that is inherently transparent and easy to interpret.
* **Strong Low-Data Performance:** While traditional neural-only baselines require vast amounts of data, this neuro-symbolic approach demonstrates superior performance in low-data settings, highlighting its potential for practical, real-world food safety applications where large datasets are not always available.

This work represents a significant step towards building more trustworthy and transparent AI systems for critical domains like food safety.

*You can read the full paper [here](/files/Towards_Explainable_FoodHazard.pdf).*