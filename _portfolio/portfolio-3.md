---
title: "Probing on Machine Translation Quality Estimation Models"
excerpt: "An in-depth evaluation of model behavior in multilingual machine translation quality estimation.<br/><img src='/images/probing.png'>"
collection: portfolio
---

**Supervisor**: [Prof. Lucia Specia](https://www.imperial.ac.uk/people/l.specia), [Dr. Marina Fomicheva](https://lama.doc.ic.ac.uk/team/marina) 

**Objective**:  Dive deep into understanding the internal mechanics of the models for multilingual machine translation quality estimation (MTQE), with a primary focus on  `TransQuest`, a then state-of-the-art solution in 2020. 

**Approach**:  

- Conducted rigorous experiments with the TransQuest model to gauge its performance.  
- Explored alternate representations by integrating the Canonical Correlation Analysis (CCA) transformation in sentence embedding. Implemented both linear and deep versions of CCA.
- Employed a sentence retrieval task to observe the implications of the CCA transform. 
- Undertook probing experiments, assessing the impact of diverse training and testing datasets on MTQE model behavior. 

**Key Findings**:

1. Linear CCA proves adept at capturing similarities between source and target sentences.
2. TransQuest effectively manages intra-language noise during training but struggles with inter-language interference.
3. TransQuest predominantly relies on target sentence fluency for quality estimation, with source complexity playing a secondary role.
4. In evaluations, while TransQuest balances its dependency between source and target texts, the DCCA-based model exhibits a stronger inclination towards target text, showing heightened sensitivity to its noise.

**Conclusion**: 
This exploration yielded insights into how MTQE models, especially TransQuest, function under varied scenarios. It also spotlighted potential areas for refinement and set the stage for future innovations in machine translation quality estimation.
