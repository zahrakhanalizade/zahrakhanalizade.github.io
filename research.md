---
layout: default
title: "Research"
---
## [Home](./index.md) | [Research](./research.md) | [Teaching](./teaching.md) | [CV](./cv.md) | [Blog](./misc.md)

## My Research

### **Prioritized Ranking Experimental Design Using Recommender Systems in Two-Sided Platforms**
**Mahyar Habibi, Zahra Khanalizadeh, Negar Ziaeian**  
📄 [Read on arXiv](https://www.arxiv.org/abs/2502.09806)  
🎤 Presented at [CODE@MIT 2024](https://ide.mit.edu/events/code24/) (October 2024)  
🎤 Scheduled to present at [Frontiers of Online Advertising](https://sites.google.com/view/ec25-ad-workshop/) at [ACM EC 2025](https://ec25.sigecom.org/) (July 2025)

**Abstract:** Interdependencies between units in online two-sided marketplaces complicate estimating causal effects in experimental settings. We propose a novel experimental design to mitigate the interference bias in estimating the total average treatment effect (TATE) of item-side interventions in online two-sided marketplaces. Our Two-Sided Prioritized Ranking (TSPR) design uses the recommender system as an instrument for experimentation. TSPR strategically prioritizes items based on their treatment status in the listings displayed to users. We designed TSPR to provide users with a coherent platform experience by ensuring access to all items and a consistent realization of their treatment by all users. We evaluate our experimental design through simulations using a search impression dataset from an online travel agency. Our methodology closely estimates the true simulated TATE, while a baseline item-side estimator significantly overestimates TATE.

### **Extending the Reproductive Horizon: Exploring Beliefs, Preferences, and Decision-Making**
**Negar Ziaeian, Zahra Khanalizadeh**

**Abstract:** Women face unique biological constraints on fertility that shape their educational and career decisions in ways not experienced by men. As fertility declines significantly after age 35, delaying childbearing to invest in high-paying, high-powered careers often comes at a steep personal cost. Assisted Reproductive Technologies such as In Vitro Fertilization (IVF) offer a potential way to relax these tradeoffs, but their broader impact on women’s decision-making remains understudied.

This project examines how access to IVF influences women’s beliefs, fertility timing, and career choices. Using original survey data and a discrete choice framework, we estimate women’s willingness to accept delaying or forgoing motherhood in exchange for higher lifetime earnings. Our findings provide new insights into how fertility-extending technologies may reshape gendered patterns in economic and personal life decisions.


### **Distinguishing Biases from Personal Preferences: An ‘Honest’ Machine Learning Approach**
**Mahyar Habibi, Zahra Khanalizadeh, Negar Ziaeian**  
📄 [Extended Abstract](/files/Abstract_Separating_Biases_from_Preferences.pdf)  

**Abstract:** This study proposes a new method for estimating biases at the micro-level in scenarios with multiple bilateral interactions, where the presence of individual preferences and correlated characteristics complicates the analysis.  The proposed method comprises two stages. In the first stage, the method introduces a novel approach to extract preferences and characteristics, employing Collaborative Filtering with an 'honest' design. This technique is designed to separate preferences and self-induced outcomes from the constructed embeddings of interacting units. In the second stage, the method utilizes a Double Machine Learning estimator to identify biases at the unit level, based on the embeddings generated in the first stage. The methodology was applied to a dataset of nearly 150,000 film ratings by professional critics, aiming to uncover personal biases among critics towards films directed by women. The results indicate that approximately 5% of critics show a significant bias in favor of films directed by women, once personal preferences and film characteristics are accounted for. However, a ‘naive’ approach that ignores these elements suggests a much higher prevalence of bias among critics. 
