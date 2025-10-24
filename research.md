---
layout: default
title: "Research"
---
## [Home](./index.md) | [Research](./research.md) | [Teaching](./teaching.md) | [CV](./cv.md) | [Blog](./misc.md)

## My Research

### **Two-Sided Prioritized Ranking: A Coherency-Preserving Design for Marketplace Experiments**
**Job Market Paper**  
*Based on joint work with Mahyar Habibi and Negar Ziaeian.*  
📄 [Latest version (PDF)](https://zahrakhanalizade.github.io/files/JMP.pdf)  
🎤 Presented at [CODE@MIT 2024](https://ide.mit.edu/events/code24/) (October 2024)  
🎤 Poster presentation at [Frontiers of Online Advertising](https://sites.google.com/view/ec25-ad-workshop/) at [ACM EC 2025](https://ec25.sigecom.org/) (July 2025)

**Abstract:** In online two-sided marketplaces, maintaining coherence in observable item attributes, such as prices, is crucial for providing users with a consistent platform experience. For certain interventions, notably those involving price adjustments, it is vital that all users see identical realizations of treatment to prevent confusion or perception of unfairness. However, this constraint complicates causal estimation of treatment effects due to interference between marketplace units. To address this challenge, we propose a novel experimental design called Two-Sided Prioritized Ranking (TSPR), which leverages the marketplace's recommender system as an experimental instrument. TSPR strategically prioritizes items based on their treatment status while ensuring that all users have coherent exposure to treatments. Through simulations using search impression data from an online travel agency, we demonstrate that our TSPR method accurately estimates the Total Average Treatment Effect (TATE), while traditional baseline item-side estimators, which also satisfy the coherency constraint, substantially overestimate this effect.

### **Extending the Reproductive Horizon: Exploring Beliefs, Preferences, and Decision-Making**
**Negar Ziaeian, Zahra Khanalizadeh**

**Abstract:** Women face unique biological constraints on fertility that shape their educational and career decisions in ways not experienced by men. As fertility declines significantly after age 35, delaying childbearing to invest in high-paying, high-powered careers often comes at a steep personal cost. Assisted Reproductive Technologies such as In Vitro Fertilization (IVF) offer a potential way to relax these tradeoffs, but their broader impact on women’s decision-making remains understudied.

This project examines how access to IVF influences women’s beliefs, fertility timing, and career choices. Using original survey data and a discrete choice framework, we estimate women’s willingness to accept delaying or forgoing motherhood in exchange for higher lifetime earnings. Our findings provide new insights into how fertility-extending technologies may reshape gendered patterns in economic and personal life decisions.


### **Distinguishing Biases from Personal Preferences: An ‘Honest’ Machine Learning Approach**
**Mahyar Habibi, Zahra Khanalizadeh, Negar Ziaeian**  
📄 [Extended Abstract](/files/Abstract_Separating_Biases_from_Preferences.pdf)  

**Abstract:** This study proposes a new method for estimating biases at the micro-level in scenarios with multiple bilateral interactions, where the presence of individual preferences and correlated characteristics complicates the analysis.  The proposed method comprises two stages. In the first stage, the method introduces a novel approach to extract preferences and characteristics, employing Collaborative Filtering with an 'honest' design. This technique is designed to separate preferences and self-induced outcomes from the constructed embeddings of interacting units. In the second stage, the method utilizes a Double Machine Learning estimator to identify biases at the unit level, based on the embeddings generated in the first stage. The methodology was applied to a dataset of nearly 150,000 film ratings by professional critics, aiming to uncover personal biases among critics towards films directed by women. The results indicate that approximately 5% of critics show a significant bias in favor of films directed by women, once personal preferences and film characteristics are accounted for. However, a ‘naive’ approach that ignores these elements suggests a much higher prevalence of bias among critics. 
