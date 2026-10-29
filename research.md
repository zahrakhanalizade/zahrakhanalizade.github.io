---
layout: default
title: "Research"
---
## [Home](./index.md) | [Research](./research.md) | [Teaching](./teaching.md) | [CV](./cv.md) | [Blog](./misc.md)

## My Research


### **Two-Sided Prioritized Ranking: A Coherency-Preserving Design for Marketplace Experiments** [[Paper]](https://arxiv.org/abs/2502.09806)
**Job Market Paper**;   
*joint work with Mahyar Habibi and Negar Ziaeian.*  
_forthcoming In Equity and Access in Algorithms, Mechanisms, and Optimization (EAAMO ’26)_  
  
Presented at [CODE@MIT 2024](https://ide.mit.edu/events/code24/) (October 2024)  
Poster presentation at [Frontiers of Online Advertising](https://sites.google.com/view/ec25-ad-workshop/) at [ACM EC 2025](https://ec25.sigecom.org/) (July 2025)

**Abstract:** Online marketplaces frequently run pricing experiments in environments where users choose from a list of items. In these settings, items compete for users’ limited attention and demand, creating interference among items within a list: Changing prices for any item can affect the demand for others, biasing estimates from item-level A/B tests. In addition, a key consideration in pricing experiments is preserving platform coherency across prices and item availability. This requirement rules out experimental designs such as user-level A/B tests as they violate platform coherency. We propose Two-Sided Prioritized Ranking (TSPR) to estimate the total average treatment effect of price changes in such settings. TSPR exploits position bias in ranked search results to create variation in treatment exposure without compromising coherency. TSPR randomizes both users and items and reorders ranked lists, prioritizing treated items for one group of users and untreated items for the other. All users see the same items at consistent prices, but differ in exposure to treatment as they pay disproportionate attention across ranks. In semi-synthetic simulations based on Expedia hotel search data, TSPR outperforms baseline coherency-preserving experiment designs by reducing estimation bias and providing sufficient statistical power.

---


### **Distinguishing Biases from Personal Preferences: An Honest Machine Learning Approach** [[Paper]](https://zahrakhanalizade.github.io/files/HonestCF.pdf)
*Mahyar Habibi, Zahra Khanalizadeh, Negar Ziaeian*    
 Accepted for presentation at [IAAE 2026 Annual Conference](https://iaae2026.pages.dev/) (June 2026);
 Poster at ACM EAAMO 2026 

<!-- [[Extended Abstract]](/files/Abstract_Separating_Biases_from_Preferences.pdf)  -->

**Abstract:** This study proposes a new method for estimating biases at the micro-level in scenarios with multiple bilateral interactions, where the presence of individual preferences and correlated characteristics complicates the analysis.  The proposed method comprises two stages. In the first stage, the method introduces a novel approach to extract preferences and characteristics, employing Collaborative Filtering with an 'honest' design. This technique is designed to separate preferences and self-induced outcomes from the constructed embeddings of interacting units. In the second stage, the method utilizes a Double Machine Learning estimator to identify biases at the unit level, based on the embeddings generated in the first stage. Monte Carlo simulations demonstrate that HCF+DML substantially outperforms naive OLS estimation under confounding, reducing RMSE by up to 50% and maintaining high correlation with true parameters even under embedding misspecification and non-random selection. We apply the method to nearly 150,000 film reviews from professional critics to estimate gender-based 
bias in evaluations of female-directed films. Naive comparisons suggest that 29% of critics exhibit statistically significant favoritism toward female directors. After controlling for the match between critic preferences and film characteristics, this figure drops to under 1%. The apparent pro-female pattern largely reflects critics' preferences for genres where female directors are disproportionately represented, rather 
than gender-based favoritism per se.

---

### **Extending the Reproductive Horizon: Exploring Beliefs, Preferences, and Decision-Making** [[Paper]](https://warwick.ac.uk/fac/soc/economics/staff/ziaeianghasemzadeh/jmp_negar-ziaeian.pdf)
*Joint work with Negar Ziaeian*    
Poster presentation at [PAA 2026 Annual Meeting](https://www.populationassociation.org/paa2026/home) (May 2026)

**Abstract:** Female fertility declines with age, and in vitro fertilization (IVF) is the main technology available to extend it, yet many women misjudge what it costs and how often it succeeds. We test whether correcting these misperceptions changes women’s career-family timing decisions in an experiment with 635 UK women aged 20-30. Women overestimate their natural fertility and misperceive IVF’s cost and success rate, while judging motherhood’s labour-market cost fairly accurately. Randomly treating women with information about IVF’s true cost or true success rate moves cost beliefs 83% and success beliefs 52% toward the truth, yet neither changes how much income women will forgo for a career allowing earlier motherhood. The null holds regardless of how wrong a woman’s prior belief was, across observed characteristics, and in incentivized choices. However, success information lowers demand for egg-freezing information, an insurance against a future IVF attempt. IVF misperceptions are substantial and correctable but do not constrain the career-family timing decision.


