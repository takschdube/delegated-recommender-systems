# Delegated Recommender Systems

A curated reading list on recommender systems in which AI agents act for users, sellers, advertisers, or platforms. We call this regime **delegated recommendation**. Shopping agents search and buy for users, sellers optimize listings for the agents that read them, advertisers bid through automated agents, and platforms deploy agents of their own.

The list accompanies the survey *Delegated Recommender Systems: A Survey of AI Agents and Mechanism Design* (arXiv version forthcoming).

## How the list is organized

Papers are grouped by where the decision is made:

- **Filter**: the platform learns a ranking from interaction data.
- **Generate**: the platform generates items, text, or data with a generative model.
- **Delegate**: an AI agent decides for a user, seller, advertiser, or platform.

Delegate papers carry an approach tag: `Learning-based` (AI methods), `Analytical` (mechanism design, game theory, economic models), `Empirical` (measurements of AI agents), or `Position`. Within each section, papers are sorted newest first.

## Contents

- [Surveys](#surveys)
- [Position papers and perspectives](#position-papers-and-perspectives)
- [Delegate: AI agents on every side](#delegate-ai-agents-on-every-side)
- [Foundations: recommender systems as mechanisms](#foundations-recommender-systems-as-mechanisms)
- [Generate: generative recommenders](#generate-generative-recommenders)
- [Filter: learning from interaction data](#filter-learning-from-interaction-data)
- [Benchmarks, sandboxes, and evaluation](#benchmarks-sandboxes-and-evaluation)
- [Industry developments](#industry-developments)
- [Contributing](#contributing)

## Surveys

- [Agentic Commerce and SME Competitiveness: An Integrative Review and Theory-Informed Research Framework](https://doi.org/10.62222/krva3141). Al-Dawoodii and Večeřová. *Journal of Business Sectors 2026*.
- [Agentic Commerce: A Survey of How AI Agents Are Reshaping Commerce](https://doi.org/10.36227/techrxiv.176972193.39211542/v1). Zhang et al. *TechRxiv 2026*.
- [Agentic Commerce: A Systematic Review of AI-Driven Autonomous Shopping and Emerging Transaction Protocols](https://doi.org/10.66556/2787-9364.3-6.halat-o). Halat. *Global Prosperity 2026*.
- [Autonomous Information Seeking: A Roadmap for Agentic Recommender Systems](https://arxiv.org/abs/2607.04433). Lin et al. *arXiv 2026*.
- [From Recommendations to Delegation: A Systematic Review Mapping Agentic AI in E-Commerce and Its Consumer Effects](https://doi.org/10.3390/info17030222). Balaskas. *Information (MDPI) 2026*.
- [Optimizing Visibility in Generative Engines: A Critical Survey of Generative Engine Optimization (2023-2026)](https://arxiv.org/abs/2607.14035). Martínez. *arXiv 2026*.
- [Reproducibility in Recommender Systems: A Survey](https://arxiv.org/abs/2607.26074). Said and Bellogin. *arXiv 2026*.
- [A Survey on Generative Recommendation: Data, Model, and Tasks](https://arxiv.org/abs/2510.27157). Hou et al. *AI Open 2025*.
- [A Survey on LLM-powered Agents for Recommender Systems](https://arxiv.org/abs/2502.10050). Peng et al. *EMNLP Findings 2025*.
- [Agentic Markets: Game Dynamics and Equilibrium in Markets with Learning Agents](https://arxiv.org/abs/2506.18571). Bichler et al. *arXiv 2025*.
- [Algorithmic Delegated Choice: An Annotated Reading List](https://arxiv.org/abs/2508.06562). Hajiaghayi and Shin. *SIGecom Exchanges 2025*.
- [An Economy of AI Agents](https://arxiv.org/abs/2509.01063). Hadfield and Koh. *arXiv 2025*.
- [The Future is Agentic: Definitions, Perspectives, and Open Challenges of Multi-Agent Recommender Systems](https://arxiv.org/abs/2507.02097). Maragheh and Deldjoo. *ACM TORS 2025*.
- [Towards Trustworthy AI-Empowered Real-Time Bidding for Online Advertisement Auctioning](https://arxiv.org/abs/2210.07770). Tang and Yu. *ACM Computing Surveys 2025*.
- [A Review of Modern Recommender Systems Using Generative Models (Gen-RecSys)](https://arxiv.org/abs/2404.00579). Deldjoo et al. *KDD 2024*.
- [Auto-Bidding and Auctions in Online Advertising: A Survey](https://arxiv.org/abs/2408.07685). Aggarwal et al. *SIGecom Exchanges 2024*.
- [Large Language Model Enhanced Recommender Systems: A Survey](https://arxiv.org/abs/2412.13432). Liu et al. *arXiv 2024*.
- [A survey on large language models for recommendation](https://arxiv.org/abs/2305.19860). Wu et al. *World Wide Web Journal 2023*.
- [Graph Neural Networks in Recommender Systems: A Survey](https://arxiv.org/abs/2011.02260). Wu et al. *ACM Computing Surveys 2022*.
- [A Survey of Graph Neural Networks for Recommender Systems: Challenges, Methods, and Directions](https://arxiv.org/abs/2109.12843). Gao et al. *ACM TORS 2021*.

## Position papers and perspectives

- [Agentic markets](https://doi.org/10.1007/s12525-026-00906-y). Bichler. *Electronic Markets 2026*.
- [Generative AI Advertising as a Problem of Trustworthy Commercial Intervention](https://arxiv.org/abs/2605.18673). Qiu and Mei. *arXiv 2026*.
- [Position: Recommender Systems Should Move Beyond Platform-Centric Ranking toward Personal Agent-Mediated Recommendation](https://arxiv.org/abs/2609.11942). Yuan et al. *arXiv 2026*.
- [The Agentic Economy](https://arxiv.org/abs/2505.15799). Rothschild et al. *CACM 2026*.
- [The Coasean Singularity? Demand, Supply, and Market Design with AI Agents](https://www.nber.org/books-and-chapters/economics-transformative-ai/coasean-singularity-demand-supply-and-market-design-ai-agents). Shahidi et al. *NBER volume 2026*.
- [The Evolution of Digital Search: From Blue Links to Delegated Decision-Making](https://arxiv.org/abs/2607.21459). Rothschild et al. *arXiv 2026*.
- [The Next Paradigm Is User-Centric Agent, Not Platform-Centric Service](https://arxiv.org/abs/2602.15682). Zhang et al. *arXiv 2026*.
- [User-Controlled Intent Layers for LLM-Mediated Personalization: A Research Agenda for Recommender Systems](https://doi.org/10.1145/3773078.3831743). Liu et al. *RecSys 2026*.
- [Agentic Web: Weaving the Next Web with AI Agents](https://arxiv.org/abs/2507.21206). Yang et al. *arXiv 2025*.
- [Towards Agentic Recommender Systems in the Era of Multimodal Large Language Models](https://arxiv.org/abs/2503.16734). Huang et al. *arXiv 2025*.
- [Virtual Agent Economies](https://arxiv.org/abs/2509.10147). Tomasev et al. *arXiv 2025*.
- [Generative AI as Economic Agents](https://arxiv.org/abs/2406.00477). Immorlica et al. *SIGecom Exchanges 2024*.
- [Online Advertisements with LLMs: Opportunities and Challenges](https://arxiv.org/abs/2311.07601). Feizi et al. *SIGecom Exchanges 2023*.

## Delegate: AI agents on every side

### III.1 User-side agents

- [Delegation Asymmetry in Agentic Recommender Systems: Measuring Two-Sided Receptivity in Online Dating](https://arxiv.org/abs/2608.18058). Leshchikova et al. *WSDM 2027*. `Empirical` Measures two-sided willingness to accept agent-mediated messages in online dating.
- [Agentic Markets: Equilibrium Effects of Improving Consumer Search](https://arxiv.org/abs/2603.25893). Lucier et al. *arXiv 2026*. `Analytical` Equilibrium effects of AI-improved consumer search on learning and welfare.
- [Et Tu, Brute? Economic Misalignment in Personal AI Agents](https://arxiv.org/abs/2609.24927). Priyanshu et al. *arXiv 2026*. `Empirical` Personal agents steer recommendations by the user's inferred wealth.
- [From Product Search to Preference Articulation: The Economics of Agentic Commerce](https://arxiv.org/abs/2608.08395). Dong et al. *arXiv 2026*. `Analytical` Agentic versus manual search when preferences are hard to articulate.
- [Towards Next-Generation Recommender Systems: A Benchmark for Personalized Recommendation Assistant with LLMs](https://arxiv.org/abs/2503.09382). Huang et al. *WSDM 2026*. `Empirical` Benchmark of LLMs as personal recommendation assistants with hard and soft user conditions.
- [When Is Delegated Play Truthful? Within-Range Regret and the Trilemma of Aligned Delegation](https://arxiv.org/abs/2607.14357). Dube. *arXiv 2026*. `Analytical` When principals should report truthfully to AI proxies; a trilemma of aligned delegation.
- [Whom Do AI Agents Work For? Role Assignment Induces Sponsorship Bias in LLM Recommenders](https://arxiv.org/abs/2609.17989). Wadi and Ma. *arXiv 2026*. `Empirical` Assigning an agent the platform's role increases its bias toward sponsored listings.
- [iAgent: LLM Agent as a Shield between User and Recommender Systems](https://arxiv.org/abs/2502.14662). Xu et al. *ACL Findings 2025*. `Learning-based` A user-side LLM agent that shields the user and re-ranks platform recommendations.
- [Magentic Marketplace: An Open-Source Environment for Studying Agentic Markets](https://arxiv.org/abs/2510.25779). Bansal et al. *arXiv 2025*. `Empirical` Open-source environment for agentic markets; finds first-proposal bias and manipulation risks.
- [What Is Your AI Agent Buying? Evaluation, Biases, Model Dependence, & Emerging Implications for Agentic E-Commerce](https://arxiv.org/abs/2508.02630). Allouah et al. *arXiv 2025*. `Empirical` Shopping agents concentrate demand, show position bias, and reward sellers who edit listings.

### III.2 Supply-side agents

- [AX is the New AEO](https://arxiv.org/abs/2609.34951). Finder et al. *arXiv 2026*. `Position` Argues that businesses must optimize for agents that read results and act on them.
- [When Optimization Becomes Manipulation: Defending Generative Search against Malicious Generative Engine Optimization](https://arxiv.org/abs/2609.02964). Li et al. *arXiv 2026*. `Learning-based` Defends generative search against malicious generative engine optimization.
- [E-GEO: A Testbed for Generative Engine Optimization in E-Commerce](https://arxiv.org/abs/2511.20867). Bagga et al. *arXiv 2025*. `Empirical` Testbed for generative engine optimization in e-commerce.
- [Clickbait vs. Quality: How Engagement-Based Optimization Shapes the Content Landscape in Online Platforms](https://arxiv.org/abs/2401.09804). Immorlica et al. *WWW 2024*. `Analytical` Engagement-based ranking rewards clickbait and can underperform random recommendation.
- [GEO: Generative Engine Optimization](https://arxiv.org/abs/2311.09735). Aggarwal et al. *KDD 2024*. `Learning-based` Black-box optimization of web content for visibility in generative engines.
- [Human vs. Generative AI in Content Creation Competition: Symbiosis or Conflict?](https://arxiv.org/abs/2402.15467). Yao et al. *ICML 2024*. `Analytical` A contest model of competition between human and generative AI creators.
- [Manipulating Large Language Models to Increase Product Visibility](https://arxiv.org/abs/2404.07981). Kumar and Lakkaraju. *arXiv 2024*. `Empirical` Strategic text sequences lift a product to the top of LLM recommendations.
- [Ranking Manipulation for Conversational Search Engines](https://arxiv.org/abs/2406.03589). Pfrommer et al. *EMNLP 2024*. `Empirical` Prompt injection in web content manipulates rankings of conversational search engines.
- [User Welfare Optimization in Recommender Systems with Competing Content Creators](https://arxiv.org/abs/2404.18319). Yao et al. *KDD 2024*. `Analytical` Platform signaling steers competing creators toward higher user welfare.

### III.3 Advertiser-side mechanisms

- [From Conversations to Mechanisms: Aligning Advertiser Incentives in AI-Powered Product Recommendations](https://elischolar.library.yale.edu/cowles-discussion-paper-series/2941/). Bergemann et al. *Cowles Foundation DP 2026*. `Analytical` Payments conditioned on user feedback align advertisers in AI shopping assistants.
- [LLM-Auction: Generative Auction towards LLM-Native Advertising](https://arxiv.org/abs/2512.10551). Zhao et al. *arXiv 2025*. `Learning-based` A generative auction for ads integrated into LLM output.
- [Sponsored Questions and How to Auction Them](https://arxiv.org/abs/2512.03975). Bhawalkar et al. *arXiv 2025*. `Analytical` Auctions for sponsored clarifying questions when a conversational AI resolves ambiguous queries.
- [Ad Auctions for LLMs via Retrieval Augmented Generation](https://arxiv.org/abs/2406.09459). Hajiaghayi et al. *NeurIPS 2024*. `Analytical` Segment auctions that place ads in retrieval-augmented LLM output.
- [AIGB: Generative Auto-bidding via Diffusion Modeling](https://arxiv.org/abs/2405.16141). Guo et al. *KDD 2024*. `Learning-based` Auto-bidding as conditional diffusion over bid trajectories.
- [Auctions with LLM Summaries](https://arxiv.org/abs/2404.08126). Dubey et al. *KDD 2024*. `Analytical` Incentive-compatible auctions for placement inside LLM-generated summaries.
- [Mechanism Design for Large Language Models](https://arxiv.org/abs/2310.10826). Dütting et al. *WWW 2024*. `Analytical` Token auctions that aggregate LLM outputs from self-interested agents.
- [Truthful Aggregation of LLMs with an Application to Online Advertising](https://arxiv.org/abs/2405.05905). Soumalias et al. *NeurIPS 2024*. `Analytical` Truthful aggregation of LLM outputs, applied to online advertising.

### III.4 Platform side

- [A Position Paper on Recommender Systems in the Era of Autonomous Agents](https://arxiv.org/abs/2607.24822). Sun. *RecSys 2026*. `Position` Defines human, agent, and platform interactions for recommendation with autonomous agents.
- [Mixture-of-Experts Knowledge Graph Retrieval-Augmented Generation for Multi-Agent LLM-based Recommendation](https://arxiv.org/abs/2605.28175). Wang et al. *KDD 2026*. `Learning-based` Multi-agent LLM recommender with mixture-of-experts knowledge-graph retrieval.
- [The User Asks, Platforms Compete: How Agentic Recommendation Markets Take Shape](https://arxiv.org/abs/2607.25253). Hong et al. *arXiv 2026*. `Empirical` Platforms compete for user agents in an LLM testbed of recommendation markets.
- [Why Does AI Platform Competition Diverge? A Dynamic Analysis of Adoption, Recommendation Mechanisms, and Price Feedback](https://doi.org/10.3390/systems14080945). Yan et al. *Systems 2026*. `Analytical` Dynamic model of AI adoption, recommendation amplification, price feedback, and platform competition.
- [Who Are We Recommending To? Recommender Systems in the Agentic Web](https://arxiv.org/abs/2609.11945). Abdollahpouri et al. *RecSys 2026*. `Position` Recommendation when agents are the audience; proposes a delegation spectrum.
- [Envisioning Recommendations on an LLM-Based Agent Platform](https://doi.org/10.1145/3699952). Zhang et al. *CACM 2025*. `Position` Envisions items and recommenders as agents on an LLM-based agent platform.
- [Decoupled Recommender Systems: Exploring Alternative Recommender Ecosystem Designs](https://arxiv.org/abs/2503.03606). Buhayh et al. *arXiv 2025*. `Analytical` Models recommender ecosystems in which recommendation algorithms are decoupled from platforms and compares utility across consumers, providers, and platforms.
- [Modeling Recommender Ecosystems: Research Challenges at the Intersection of Mechanism Design, Reinforcement Learning and Generative Models](https://arxiv.org/abs/2309.06375). Boutilier et al. *arXiv 2023*. `Position` Research agenda for recommender ecosystems through mechanism design and reinforcement learning.

### III.5 Market-level effects

- [Strategic Algorithmic Monoculture: Experimental Evidence from Coordination Games](https://arxiv.org/abs/2604.09502). Ballestero et al. *arXiv 2026*. `Empirical` Experiments on strategic algorithmic monoculture in coordination games.
- [Tempting the Agent: The Economics of Reputation without Persistent Identity in AI Agent Markets](https://arxiv.org/abs/2609.02992). Gatta et al. *arXiv 2026*. `Analytical` When reputation disciplines AI agents whose identities are cheap to replace.
- [Algorithmic Collusion by Large Language Models](https://arxiv.org/abs/2404.00806). Fish et al. *arXiv 2024*. `Empirical` LLM pricing agents reach supracompetitive prices and profits.

## Foundations: recommender systems as mechanisms

### Information design and incentivized exploration

- [Exploration and Persuasion](https://arxiv.org/abs/2410.17086). Slivkins. *arXiv 2024*.
- [Recommender Systems as Mechanisms for Social Learning](https://doi.org/10.1093/QJE/QJX044). Che and Hörner. *QJE 2018*.
- [Bayesian Incentive-Compatible Bandit Exploration](https://arxiv.org/abs/1502.04147). Mansour et al. *EC 2015*.
- [Implementing the “Wisdom of the Crowd”](https://doi.org/10.1086/676597). Kremer et al. *JPE 2014*.

### Strategic users and performative prediction

- [Performative Prediction: Past and Future](https://arxiv.org/abs/2310.16608). Hardt and Mendler-Dünner. *Statistical Science 2023*.
- [Recommending to Strategic Users](https://arxiv.org/abs/2302.06559). Haupt et al. *arXiv 2023*.
- [Performative Prediction](https://arxiv.org/abs/2002.06673). Perdomo et al. *ICML 2020*.

### Strategic content creators

- [How Bad is Top-K Recommendation under Competing Content Creators?](https://arxiv.org/abs/2302.01971). Yao et al. *ICML 2023*.
- [Modeling Content Creator Incentives on Algorithm-Curated Platforms](https://arxiv.org/abs/2206.13102). Hron et al. *ICLR 2023*.
- [Supply-Side Equilibria in Recommender Systems](https://arxiv.org/abs/2206.13489). Jagadeesan et al. *NeurIPS 2023*.
- [A Game-Theoretic Approach to Recommendation Systems with Strategic Content Providers](https://arxiv.org/abs/1806.00955). Ben-Porat and Tennenholtz. *NeurIPS 2018*.

### Ad auctions and marketplace ranking

- [Games, Markets, and Online Learning](https://doi.org/10.1017/9781009711265). Kroer. *Cambridge University Press 2026*.
- [How Should Marketplaces Decide Who to Show?](https://www.sigecom.org/exchanges/volume_24/1/SHI.pdf). Shi. *SIGecom Exchanges 2026*.
- [Internet Advertising and the Generalized Second-Price Auction: Selling Billions of Dollars Worth of Keywords](https://doi.org/10.1257/aer.97.1.242). Edelman et al. *AER 2007*.
- [Position auctions](https://doi.org/10.1016/j.ijindorg.2006.10.002). Varian. *IJIO 2007*.

### Matching, multistakeholder recommendation, and delegated choice

- [Beyond Personalization: Research Directions in Multistakeholder Recommendation](https://arxiv.org/abs/1905.01986). Abdollahpouri et al. *arXiv 2019*.
- [Delegated Search Approximates Efficient Search](https://arxiv.org/abs/1806.06933). Kleinberg and Kleinberg. *EC 2018*.
- [A Model of Delegated Project Choice](https://doi.org/10.3982/ecta7965). Armstrong and Vickers. *Preprint 2008*.
- [College Admissions and the Stability of Marriage](https://doi.org/10.2307/2312726). Gale and Shapley. *American Mathematical Monthly 1962*.

### Collusion and monoculture

- [Picking on the Same Person: Does Algorithmic Monoculture lead to Outcome Homogenization?](https://arxiv.org/abs/2211.13972). Bommasani et al. *NeurIPS 2022*.
- [Algorithmic monoculture and social welfare](https://arxiv.org/abs/2101.05853). Kleinberg and Raghavan. *PNAS 2021*.
- [Artificial Intelligence, Algorithmic Pricing, and Collusion](https://doi.org/10.1257/AER.20190623). Calvano et al. *AER 2020*.

## Generate: generative recommenders

### II.1 Diffusion recommenders

- [Continuous-time Discrete-space Diffusion Model for Recommendation](https://doi.org/10.1145/3773966.3777987). Liu et al. *WSDM 2026*.
- [Dual Conditional Diffusion for Sequential Recommendation](https://doi.org/10.1145/3773966.3777926). Huang et al. *WSDM 2026*.
- [DimeRec: A Unified Framework for Enhanced Sequential Recommendation via Generative Diffusion Models](https://arxiv.org/abs/2408.12153). Li et al. *WSDM 2025*.
- [Denoising Diffusion Recommender Model](https://arxiv.org/abs/2401.06982). Zhao et al. *SIGIR 2024*.
- [Diffusion Recommender Model](https://arxiv.org/abs/2304.04971). Wang et al. *SIGIR 2023*.

### II.2 LLM-based recommenders

- [Hybrid Dual-Semantics Modeling for Enhancing Large Language Model Based Recommendation](https://doi.org/10.1145/3773966.3777943). Liu et al. *WSDM 2026*.
- [Leveraging Retrieval-Augmented Language Models for Accurate Item/Feature Selection in Conversational Recommender Systems](https://doi.org/10.1145/3773966.3777947). Kim et al. *WSDM 2026*.
- [MGFRec: Towards Reinforced Reasoning Recommendation with Multiple Groundings and Feedback](https://arxiv.org/abs/2510.22888). Cai et al. *KDD 2026*.
- [On-Device Large Language Models for Sequential Recommendation](https://arxiv.org/abs/2601.09306). Xia et al. *WSDM 2026*.
- [CoT4Rec: Revealing User Preferences Through Chain of Thought for Recommender Systems](https://doi.org/10.1609/aaai.v39i12.33434). Yue et al. *AAAI 2025*.
- [Lost in Sequence: Do Large Language Models Understand Sequential Recommendation?](https://arxiv.org/abs/2502.13909). Kim et al. *KDD 2025*.
- [Unleashing the Power of Large Language Model for Denoising Recommendation](https://arxiv.org/abs/2502.09058). Wang et al. *WWW 2025*.
- [Large Language Models meet Collaborative Filtering: An Efficient All-round LLM-based Recommender System](https://arxiv.org/abs/2404.11343). Kim et al. *KDD 2024*.
- [A Bi-Step Grounding Paradigm for Large Language Models in Recommendation Systems](https://arxiv.org/abs/2308.08434). Bao et al. *ACM TORS 2023*.
- [TALLRec: An Effective and Efficient Tuning Framework to Align Large Language Model with Recommendation](https://arxiv.org/abs/2305.00447). Bao et al. *RecSys 2023*.
- [Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5)](https://arxiv.org/abs/2203.13366). Geng et al. *RecSys 2022*.

### II.3 Generative retrieval and industrial generative recommenders

- [OneLoc: Geo-Aware Generative Recommender Systems for Local Life Service](https://doi.org/10.1145/3773966.3777963). Wei et al. *WSDM 2026*.
- [Sequential Data Augmentation for Generative Recommendation](https://doi.org/10.1145/3773966.3778000). Lee et al. *WSDM 2026*.
- [OneRec: Unifying Retrieve and Rank with Generative Recommender and Iterative Preference Alignment](https://arxiv.org/abs/2502.18965). Deng et al. *arXiv 2025*.
- [Actions Speak Louder than Words: Trillion-Parameter Sequential Transducers for Generative Recommendations](https://arxiv.org/abs/2402.17152). Zhai et al. *ICML 2024*.
- [Recommender Systems with Generative Retrieval](https://arxiv.org/abs/2305.05065). Rajput et al. *NeurIPS 2023*.

### II.4 Generative data engineering

- [A Spectral Heterogeneous Diffusion Framework for Knowledge-aware Recommendation](https://doi.org/10.1145/3773966.3777946). Li et al. *WSDM 2026*.
- [R2MR: Review and Rewrite Modality for Recommendation](https://doi.org/10.1145/3690624.3709250). Tang et al. *KDD 2025*.
- [Dataset Regeneration for Sequential Recommendation](https://arxiv.org/abs/2405.17795). Yin et al. *KDD 2024*.

## Filter: learning from interaction data

### I.1 Graph-based collaborative filtering

- [Combinatorial Optimization Perspective based Framework for Multi-behavior Recommendation](https://arxiv.org/abs/2502.02232). Zhai et al. *KDD 2025*.
- [Your Graph Recommenders are Provably Doing Graph Contrastive Learning](https://doi.org/10.1145/3711896.3737182). Yang et al. *KDD 2025*.
- [Enhancing Graph Contrastive Learning with Reliable and Informative Augmentation for Recommendation](https://doi.org/10.1145/3690624.3709214). Zheng et al. *KDD 2025*.
- [GPFedRec: Graph-Guided Personalization for Federated Recommendation](https://arxiv.org/abs/2305.07866). Zhang et al. *KDD 2024*.
- [Unifying Graph Convolution and Contrastive Learning in Collaborative Filtering](https://arxiv.org/abs/2406.13996). Wu et al. *KDD 2024*.
- [Are Graph Augmentations Necessary?: Simple Graph Contrastive Learning for Recommendation](https://arxiv.org/abs/2112.08679). Yu et al. *SIGIR 2022*.
- [Self-supervised Graph Learning for Recommendation](https://arxiv.org/abs/2010.10783). Wu et al. *SIGIR 2021*.
- [LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation](https://arxiv.org/abs/2002.02126). He et al. *SIGIR 2020*.
- [Neural Graph Collaborative Filtering](https://arxiv.org/abs/1905.08108). Wang et al. *SIGIR 2019*.

### I.2 Noise, bias, and the long tail

- [SAGERec: Sampling and Gating for Enhanced Long-Tail Item Recommendations](https://doi.org/10.1145/3773966.3778004). Alshabanah et al. *WSDM 2026*.
- [SAGE: Global Semantic Alignment with LLMs for Long-Tail Sequential Recommendation](https://doi.org/10.1145/3774904.3792456). Wang et al. *WWW 2026*.
- [Teach Me How to Denoise: A Universal Framework for Denoising Multi-modal Recommender Systems via Guided Calibration](https://arxiv.org/abs/2504.14214). Li et al. *WSDM 2025*.
- [Double Correction Framework for Denoising Recommendation](https://arxiv.org/abs/2405.11272). He et al. *KDD 2024*.
- [Efficient Bi-Level Optimization for Recommendation Denoising](https://arxiv.org/abs/2210.10321). Wang et al. *KDD 2023*.
- [Meta Graph Learning for Long-tail Recommendation](https://doi.org/10.1145/3580305.3599428). Wei et al. *KDD 2023*.

### I.3 Transfer and two-sided settings

- [Review-Based Hyperbolic Cross-Domain Recommendation](https://arxiv.org/abs/2403.20298). Choi et al. *WSDM 2025*.
- [Exploring Preference-Guided Diffusion Model for Cross-Domain Recommendation](https://doi.org/10.1145/3690624.3709220). Li et al. *KDD 2025*.
- [Measure Domain's Gap: A Similar Domain Selection Principle for Multi-Domain Recommendation](https://doi.org/10.1145/3711896.3737043). Wen et al. *KDD 2025*.
- [Mitigating Negative Transfer in Cross-Domain Recommendation via Knowledge Transferability Enhancement](https://doi.org/10.1145/3637528.3671799). Song et al. *KDD 2024*.
- [Revisiting Reciprocal Recommender Systems: Metrics, Formulation, and Method](https://arxiv.org/abs/2408.09748). Yang et al. *KDD 2024*.

### I.4 Sequences and long-term objectives

- [Explicit and Implicit Modeling via Dual-Path Transformer for Behavior Set-informed Sequential Recommendation](https://doi.org/10.1145/3637528.3671755). Chen et al. *KDD 2024*.
- [Retention Depolarization in Recommender System](https://doi.org/10.1145/3589334.3645485). Zhang et al. *WWW 2024*.
- [PrefRec: Recommender Systems with Human Preferences for Reinforcing Long-term User Engagement](https://arxiv.org/abs/2212.02779). Xue et al. *KDD 2023*.

## Benchmarks, sandboxes, and evaluation

Magentic Marketplace, RecBench+, and E-GEO are listed under Delegate.

### Sandboxes and datasets

- [Evaluation of Agents under Simulated AI Marketplace Dynamics](https://arxiv.org/abs/2604.14256). Kim et al. *SIGIR 2026*.
- [NaiAD: Initiate Data-Driven Research for LLM Advertising](https://arxiv.org/abs/2605.09918). Zhang et al. *arXiv 2026*.
- [AlignUSER: Human-Aligned LLM Agents via World Models for Recommender System Evaluation](https://aclanthology.org/2026.acl-long.747/). Bougie et al. *ACL 2026*.
- [User Behavior Simulation with Large Language Model-based Agents](https://arxiv.org/abs/2306.02552). Wang et al. *ACM TOIS 2025*.
- [Yambda-5B -- A Large-Scale Multi-Modal Dataset for Ranking and Retrieval](https://arxiv.org/abs/2505.22238). Ploshkin et al. *arXiv 2025*.
- [On Generative Agents in Recommendation](https://arxiv.org/abs/2310.10108). Zhang et al. *SIGIR 2024*.

### Evaluation pitfalls

- [Diffusion Recommender Models and the Illusion of Progress: A Concerning Study of Reproducibility and a Conceptual Mismatch](https://arxiv.org/abs/2505.09364). Benigni et al. *ACM TORS 2026*.
- [Improving Methodological Standards in Recommender Systems Offline Evaluation](https://doi.org/10.1145/3800587). Jannach and Chen. *ACM TORS 2026*.
- [On the Reliability of Sampling Strategies in Offline Recommender Evaluation](https://doi.org/10.1145/3705328.3748086). Pereira et al. *RecSys 2025*.
- [Time to Split: Exploring Data Splitting Strategies for Offline Evaluation of Sequential Recommenders](https://doi.org/10.1145/3705328.3748164). Gusak et al. *RecSys 2025*.
- [Don't Get Ahead of Yourself: A Critical Study on Data Leakage in Offline Evaluation of Sequential Recommenders](https://doi.org/10.1145/3705328.3759329). Le et al. *RecSys 2025*.
- [Do LLMs Memorize Recommendation Datasets? A Preliminary Study on MovieLens-1M](https://arxiv.org/abs/2505.10212). Palma et al. *SIGIR 2025*.
- [On Sampled Metrics for Item Recommendation](https://doi.org/10.1145/3394486.3403226). Krichene and Rendle. *KDD 2020*.
- [Are we really making much progress? A worrying analysis of recent neural recommendation approaches](https://arxiv.org/abs/1907.06902). Dacrema et al. *RecSys 2019*.

## Industry developments

- 2025-04: [Visa Intelligent Commerce](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21361.html) opens the Visa network to AI agent developers.
- 2025-04: [Mastercard Agent Pay](https://newsroom.mastercard.com/news/press/2025/april/mastercard-unveils-agent-pay-pioneering-agentic-payments-technology-to-power-commerce-in-the-age-of-ai) issues payment tokens to registered agents.
- 2025-09: [Google Agent Payments Protocol (AP2)](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol) for payments initiated by agents.
- 2025-09: [OpenAI and Stripe Agentic Commerce Protocol](https://stripe.com/newsroom/news/stripe-openai-instant-checkout) with Instant Checkout in ChatGPT.
- 2026-01: [Google Universal Commerce Protocol](https://techcrunch.com/2026/01/11/google-announces-a-new-protocol-to-facilitate-commerce-using-ai-agents/) with large retailers.

## Contributing

Pull requests are welcome, including for your own papers. Add one line to the right section, newest first, in this format:

```
- [Paper title](link). First author et al. *Venue Year*. `Approach` One-sentence summary.
```

The approach tag and summary are required in the Delegate section and optional elsewhere. Prefer arXiv or DOI links.

## License

[CC0 1.0](LICENSE). To the extent possible under law, the maintainers have waived all copyright to this list.
