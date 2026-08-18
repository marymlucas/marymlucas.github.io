---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from: 
  - /research/research.md
---

## Research Philosophy
My work is grounded in pragmatic innovation. I focus on advancing methodological research in applied artificial intelligence, with an emphasis on rigorous evaluation of predictive performance, fairness, and reliability under real-world conditions. My goal is to bridge cutting-edge AI methods with real-world clinical impact by developing frameworks that assess when AI systems are trustworthy enough to inform patient care, and identify where they fall short for specific populations and individual patients. This work is ultimately in service of ensuring that the benefits of clinical AI reach all patients and communities equitably.

---

## Current Research & Applied Work

**Data Science Intern** | UPHS Data Science, PennDnA at Penn Medicine | 2026–Present
  - Contribute to translational and applied AI, machine learning, and data science initiatives, including the development and evaluation of models, systems, and software, with consideration of opportunity, feasibility, and governance.

**Doctoral Research, Information Science** | Drexel University | PhD conferral September 5, 2026   
  - *Advisor*: Christopher C. Yang, PhD
  - *Committee*: Quyen Ngo, PhD; Judy Wawira Gichoya, MD, MS; Bhupesh Shetty, PhD; Erjia Yan, PhD; Grace Lu-Yao, PhD
  - *Dissertation*: *A Framework for Fair and Robust Clinical Risk Prediction through Collaborative Learning and Localized Uncertainty Quantification*

---

## Funding & Fellowships

- **NIH AIM-AHEAD Research Fellowship** (2022)  
  Supporting research in health equity, algorithmic fairness, and trustworthy AI.

- **Edith Peterson Mitchell, MD Health Equity Travel Scholarship** (2023, 2024)  
  ECOG-ACRIN Cancer Research Group Meetings.

---

## Core Focus Areas

- **Clinical AI & Predictive Modeling**  
  Developing and evaluating predictive models for clinical decision support using real-world health data, with emphasis on clinically meaningful performance and translation to practice.

- **Fairness, Robustness & Uncertainty**  
  Developing methods to evaluate and improve subgroup fairness, model reliability, and uncertainty quantification in high-stakes clinical AI systems.

- **Foundation Models in Healthcare**  
  Evaluating emerging foundation models, including large language models and tabular foundation models, for clinical applications, with emphasis on reliability, reasoning, calibration, fairness, and real-world readiness.

- **Real-World Evidence & Health Disparities**  
  Using large-scale EHR, registry, and administrative data to characterize healthcare disparities, evaluate care pathways, and generate evidence about differences in treatment and outcomes.

---

## Selected Projects

### Reliable and Robust Clinical AI  
*Algorithmic Fairness & Uncertainty Quantification*

- Designed fairness auditing frameworks for clinical risk prediction models across chronic kidney disease, substance use disorder, and oncology datasets, integrating novel mitigation techniques and benchmarking against existing approaches ([JCO CCI](https://ascopubs.org/doi/full/10.1200/CCI.23.00194){:target="_blank"}, [AIME 2025](https://doi.org/10.1007/978-3-031-95841-0_44){:target="_blank"}, [IEEE ICHI 2024](https://ieeexplore.ieee.org/document/10628594){:target="_blank"}, [IEEE ICHI 2023](https://doi.org/10.1109/ICHI57859.2023.00128){:target="_blank"}).
  - Leveraged over 10 years of clinical nursing experience to guide feature engineering and problem formulation, distinguishing true physiological signal from artifacts of clinical workflow.
  - Quantified disparities in readmission prediction and treatment completion, demonstrating how commonly used fairness metrics fail to capture systemic healthcare inequities.
- Developed a **Neighborhood-Adaptive Difficulty Score** combining k-nearest neighbor topology with conformal prediction to distinguish model limitations from inherent case complexity. <br>*(Manuscript in preparation)*

---
### Tabular Foundation Models for Clinical Prediction 
*Performance, Fairness, Calibration & Uncertainty*

  - Evaluating tabular foundation models, including **TabPFN**, **TabICL**, and **TabFM**, against established machine learning approaches on real-world clinical prediction tasks, with emphasis on predictive performance, calibration, subgroup fairness, and uncertainty quantification.
  - Investigating the use of **conformal prediction and group-specific calibration** to characterize uncertainty and subgroup reliability, including whether foundation models provide more efficient and equitable prediction sets than conventional models.
  - Initial evaluation on **MIMIC-IV sepsis mortality prediction** found tabular foundation models to be competitive with or outperform tuned classical baselines across multiple dimensions of clinical model performance and reliability. <br>*([Poster](https://doi.org/10.5281/zenodo.21809793){:target="_blank"} presented at the Emory HITI Lab Symposium 2026; manuscript in preparation)*

---

### Clinical NLP & Large Language Model Evaluation

- Developed **EnsReas**, an iterative prompting framework that improved medical question-answering accuracy and consistency on USMLE datasets (+3-5%) across both closed (GPT-4) and open-source clinical LLMs ([JAMIA](https://academic.oup.com/jamia/article/31/9/1964/7705627){:target="_blank"}).
- Applied open-source clinical LLMs to extract **pathologic TNM cancer stage** from real-world pathology reports without labeled training data, demonstrating that prompting and ensemble-based reasoning can achieve competitive performance and improved consistency relative to fine-tuned BERT baselines ([AIME 2024](https://doi.org/10.1007/978-3-031-66538-7_23){:target="_blank"}, [IEEE ICHI 2024](https://ieeexplore.ieee.org/document/10628943){:target="_blank"}).
- Designed and evaluated an LLM-assisted pipeline to automate extraction of population demographics from biomedical literature, enabling scalable equity analysis ([IJDC](https://ijdc.net/index.php/ijdc/article/view/950){:target="_blank"}, [IDCC 2026](https://doi.org/10.5281/zenodo.18924441){:target="_blank"} poster 1, [IDCC 2026](https://doi.org/10.5281/zenodo.18864397){:target="_blank"} poster 2).

---

### Real-World Evidence & Health Disparities Modeling

- Developed a mixed-order Markov chain simulation using VA Corporate Data Warehouse data to model prostate cancer treatment sequences and identify empirically observed pathways associated with elevated mortality risk across racial groups. <br>*(Manuscripts in preparation)*
- Conducted a national registry study using the AAO IRIS® Registry to quantify racial and gender disparities in retinal vein occlusion treatment via multivariable logistic regression, highlighting inequities in access to anti-VEGF therapy ([Ophthalmology Retina](https://www.ophthalmologyretina.org/article/S2468-6530(24)00043-5/abstract){:target="_blank"}).

---


[Publications](/research/publications/)