---
layout: default
title: "Research"
---
## [Home](./index.md) | [Research](./research.md) | [Teaching](./teaching.md) | [CV](./cv.md) | [Blog](./misc.md)

## My Research


### **Two-Sided Prioritized Ranking: A Coherency-Preserving Design for Marketplace Experiments**
**Job Market Paper**  
*Based on joint work with Mahyar Habibi and Negar Ziaeian.*  
[Latest version (PDF)](https://zahrakhanalizade.github.io/files/JMP.pdf)  
Presented at [CODE@MIT 2024](https://ide.mit.edu/events/code24/) (October 2024)  
Poster presentation at [Frontiers of Online Advertising](https://sites.google.com/view/ec25-ad-workshop/) at [ACM EC 2025](https://ec25.sigecom.org/) (July 2025)

**Abstract:** In online two-sided marketplaces, users must see a coherent platform environment in which all items remain accessible and item attributes, such as prices or features, are displayed consistently across users. Many interventions, especially those involving price changes, require such coherency to avoid confusion or perceptions of unfair treatment. These constraints complicate causal inference because users interact with shared items, and treatment applied to one item can spill over onto others, creating interference bias in standard A/B tests. We propose a new experimental design, Two-Sided Prioritized Ranking (TSPR), which uses the marketplace's ranking algorithm as an experimental instrument. TSPR assigns treatment through prioritized exposure while preserving coherency and limiting spillovers. Our goal is to estimate the lift, defined as the proportional change in total outcomes between counterfactual worlds in which all items are treated or untreated. Using Monte Carlo simulations based on large-scale search impression data from an online travel agency, we show that TSPR produces lift estimates that are substantially less biased than those from coherent item-side A/B tests. We also compare TSPR to cluster-randomized designs, which can reduce interference when clusters isolate exposure but require detailed knowledge of the underlying network. TSPR provides a practical and scalable alternative for platforms that must preserve coherency while obtaining reliable estimates of treatment effects.

---

### **Extending the Reproductive Horizon: Exploring Beliefs, Preferences, and Decision-Making**
*Joint work with Negar Ziaeian*    
[Extended Abstract](/files/IVF_extended_abstract.pdf)  
Scheduled poster presentation at [PAA 2026 Annual Meeting](https://www.populationassociation.org/paa2026/home) (May 2026)

**Abstract:** Limited fertility windows create a prominent tradeoff between career development and motherhood
timing. Emerging assisted reproductive technologies, such as IVF, extend this window to some degree,
and the share of IVF-conceived births continues to rise worldwide. Yet little is known about how women
incorporate access to these technologies into decisions about when to have children. This project studies
women’s beliefs about natural fertility, age-related decline, and the extent to which IVF can compensate
for biological constraints, and asks whether misperceptions about these factors influence willingness to
postpone childbearing. We field a survey and discrete choice experiment with women aged 20–30 in
the United Kingdom to measure how beliefs about fertility and IVF shape preferences over motherhood
timing and career investment. We estimate the income premium that makes respondents indifferent
between early childbearing and postponement and examine how information about IVF success and
costs shifts these tradeoffs. A real-stakes outcome complements stated preferences.

---


### **Distinguishing Biases from Personal Preferences: An Honest Machine Learning Approach**
*Mahyar Habibi, Zahra Khanalizadeh, Negar Ziaeian*  
[Extended Abstract](/files/Abstract_Separating_Biases_from_Preferences.pdf)  

**Abstract:** This study proposes a new method for estimating biases at the micro-level in scenarios with multiple bilateral interactions, where the presence of individual preferences and correlated characteristics complicates the analysis.  The proposed method comprises two stages. In the first stage, the method introduces a novel approach to extract preferences and characteristics, employing Collaborative Filtering with an 'honest' design. This technique is designed to separate preferences and self-induced outcomes from the constructed embeddings of interacting units. In the second stage, the method utilizes a Double Machine Learning estimator to identify biases at the unit level, based on the embeddings generated in the first stage. The methodology was applied to a dataset of nearly 150,000 film ratings by professional critics, aiming to uncover personal biases among critics towards films directed by women. The results indicate that approximately 5% of critics show a significant bias in favor of films directed by women, once personal preferences and film characteristics are accounted for. However, a ‘naive’ approach that ignores these elements suggests a much higher prevalence of bias among critics. 

<!--
---

### **Causal Recommendations in Two-Sided Platforms via Honest Collaborative Filtering**
*Mahyar Habibi, Zahra Khanalizadeh, Negar Ziaeian*

**Abstract:** This project extends the “honest collaborative filtering” framework introduced in *Distinguishing Biases from Personal Preferences* to a new domain of large-scale, two-sided platforms. The paper develops methods for generating micro-level causal recommendations, identifying which AI-generated ad features causally improve engagement and conversions, and for which user segments. By combining causal inference with collaborative filtering, the project aims to advance interpretable and heterogeneous recommendation systems for modern digital marketplaces.
-->
