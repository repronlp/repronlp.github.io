---
layout: splash
permalink: /
excerpt: "ReproNLP Shared Task on Reproducibility of Evaluations in NLP"
layout: single
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/reprohum_banner_orig.jpg
---

# ReproNLP 2024

# First Call for Participation

## Background

Across Natural Language Processing (NLP), a growing body of work is exploring the issue of reproducibility in machine learning contexts. The field is currently far from having a generally agreed tool box of methods for defining and assessing reproducibility. Reproducibility of results of human evaluation experiments is particularly under-addressed which is of concern for areas of NLP where human evaluation is common including e.g. MT, text generation and summarisation. More generally, human evaluations provide the benchmarks against which automatic evaluation methods are assessed across NLP.

We previously organised the First ReproGen Shared Task on reproducibility of human evaluations in NLG as part of Generation Challenges (GenChal) at INLG’21, and the Second ReproGen Shared Task at INLG’22, where we extended the scope to encompass automatic evaluation methods as well as human. Last year we expanded the scope of the shared task series to encompass all NLP tasks, renaming it the ReproNLP Shared Task on Reproducibility of Evaluations in NLP (part of the HumEval workshop at RANLP’23). This year we are focussing on human evaluations, and the results session will be held at the 4th Workshop on Human Evaluation of NLP Systems (HumEval’24 at LREC-COLING’24). 

As with the previous shared tasks, our overall aim is (i) to shed light on the extent to which past NLP evaluations have been reproducible, and (ii) to draw conclusions regarding how NLP evaluations can be designed and reported to increase reproducibility. With this task being run over several years, we hope to be able to document an overall increase in levels of reproducibility over time.

## About ReproNLP

ReproNLP has two tracks, one an ‘unshared task’ in which teams attempt to reproduce any prior evaluation results (Track B below), the other a standard shared tasks in which teams repeat existing evaluation studies with the aim of reproducing their results (Track A):

**A. Open Track**: Reproduce previous evaluation results from any paper, and report what happened. Unshared task.

**B. ReproHum Track** (papers see below): For a shared set of selected evaluation studies from the ReproHum Project, participants repeat one or more of the studies and attempt to reproduce their results, using the information provided by the ReproNLP organisers only, and following a common reproduction approach.


## Track B Papers

The specific experiments listed and described below are currently the subject of reproduction studies in the [ReproHum](https://reprohum.github.io/) project. The authors have provided very detailed information about the experiments. In some cases, we have introduced standardisations to the experimental design as noted in the detailed instructions to participants which will be shared upon registration. 

The papers and studies, with many thanks to the authors for supporting ReproHum and ReproNLP, are:


**Reif et al. (2022)**:  A Recipe for Arbitrary Text Style Transfer with Large Language Models:  [https://aclanthology.org/2022.acl-short.94](https://aclanthology.org/2022.acl-short.94)

* Absolute evaluation study; English; 3 quality criteria; 3 datasets; varies between 4 and 6 systems and between 200 and 300 evaluation items per dataset-criterion combination; crowdsourced.

**Vamvas & Sennrich (2022)**:  As Little as Possible, as Much as Necessary: Detecting Over- and Undertranslations with Contrastive Conditioning:  [https://aclanthology.org/2022.acl-short.53](https://aclanthology.org/2022.acl-short.53)

* Absolute evaluation study; ZH to EN, EN to DE; 1 quality criterion; 1 dataset; 1 system and 757 evaluation items.

**Bai et al. (2021)**:  Cross-Lingual Abstractive Summarization with Limited Parallel Resources:  [https://aclanthology.org/2021.acl-long.538](https://aclanthology.org/2021.acl-long.538)

* Relative evaluation study; ZH to EN; 3 quality criteria; 1 dataset; 4 systems and 240 evaluation items per criterion.

**Puduppully & Lapata (2021)**:  Data-to-text Generation with Macro Planning:  [https://aclanthology.org/2021.tacl-1.31/](https://aclanthology.org/2021.tacl-1.31/)

* Absolute evaluation study; English; 2 quality criteria; 2 datasets; 5 systems and 400 evaluation items per dataset-criterion combination; crowdsourced.
* Relative evaluation study; English; 3 quality criteria; 2 datasets; 5 systems and 200 evaluation items per dataset-criterion combination; crowdsourced.

**Liu et al. (2021)**:  DExperts: Decoding-Time Controlled Text Generation with Experts and Anti-Experts:  [https://aclanthology.org/2021.acl-long.522](https://aclanthology.org/2021.acl-long.522)

* Relative evaluation study; English; 3 quality criteria; 2 datasets; varies between 5 and 6 systems and between 960 and 1200 evaluation items per dataset-criterion combination; crowdsourced.

**Dwiastuti (2019)**:  English-Indonesian Neural Machine Translation for Spoken Language Domains:  [https://aclanthology.org/P19-2043](https://aclanthology.org/P19-2043)

* Relative evaluation study; Indonesian; 1 quality criterion; 1 dataset; 2 systems and 50 evaluation items.

**Hosking & Lapata (2021)**:  Factorising Meaning and Form for Intent-Preserving Paraphrasing:  [https://aclanthology.org/2021.acl-long.112](https://aclanthology.org/2021.acl-long.112)

* Relative evaluation study; English; 3 quality criteria; 1 dataset; 4 systems and 1200 evaluation items per criterion; crowdsourced.

**Atanasova et al. (2020)**:  Generating Fact Checking Explanations:  [https://aclanthology.org/2020.acl-main.656](https://aclanthology.org/2020.acl-main.656)

* Absolute evaluation study; English; 1 quality criterion; 1 dataset; 3 systems and 240 evaluation items.
* Relative evaluation study; English; 4 quality criteria; 1 dataset; 3 systems and 40 evaluation items per criterion.

**August et al. (2022)**:  Generating Scientific Definitions with Controllable Complexity:  [https://aclanthology.org/2022.acl-long.569](https://aclanthology.org/2022.acl-long.569)

* Absolute evaluation study; English; 5 quality criteria; 2 datasets; 3 systems and 300 evaluation items per dataset-criterion combination; some crowdsourced.

**Hosking et al. (2022)**:  Hierarchical Sketch Induction for Paraphrase Generation:  [https://aclanthology.org/2022.acl-long.178](https://aclanthology.org/2022.acl-long.178)

* Relative evaluation study; English; 3 quality criteria; 1 dataset; 4 systems and 1800 evaluation items per criterion; crowdsourced.

**Yao et al. (2022)**:  It is AI's Turn to Ask Humans a Question: Question-Answer Pair Generation for Children's Story Books:  [https://aclanthology.org/2022.acl-long.54](https://aclanthology.org/2022.acl-long.54)

* Absolute evaluation study; English; 3 quality criteria; 1 dataset; 3 systems and 361 evaluation items per criterion.

**Chakrabarty et al. (2022)**:  It's not Rocket Science: Interpreting Figurative Language in Narratives:  [https://aclanthology.org/2022.tacl-1.34/](https://aclanthology.org/2022.tacl-1.34/)

* Absolute evaluation study; English; 1 quality criterion; 2 datasets; varies between 6 and 8 systems and between 150 and 200 evaluation items per dataset; crowdsourced.
* Relative evaluation study; English; 1 quality criterion; 2 datasets; 3 systems and varies between 225 and 300 evaluation items per dataset; crowdsourced.

**Feng et al. (2021)**:  Language Model as an Annotator: Exploring DialoGPT for Dialogue Summarization:  [https://aclanthology.org/2021.acl-long.117](https://aclanthology.org/2021.acl-long.117)

* Absolute evaluation study; English; 3 quality criteria; 2 datasets; 7 systems and varies between 70 and 700 evaluation items per dataset-criterion combination.

**Lux & Vu (2022)**:  Language-Agnostic Meta-Learning for Low-Resource Text-to-Speech with Articulatory Features:  [https://aclanthology.org/2022.acl-long.472](https://aclanthology.org/2022.acl-long.472)

* Relative evaluation study; German; 1 quality criterion; 1 dataset; 2 systems and 12 evaluation items.

**Gu et al. (2022)**:  MemSum: Extractive Summarization of Long Documents Using Multi-Step Episodic Markov Decision Processes:  [https://aclanthology.org/2022.acl-long.450](https://aclanthology.org/2022.acl-long.450)

* Relative evaluation study; English; 3 quality criteria; 1 dataset; 2 systems and varies between 63 and 67 evaluation items per criterion.

**Gabriel et al. (2022)**:  Misinfo Reaction Frames: Reasoning about Readers' Reactions to News Headlines:  [https://aclanthology.org/2022.acl-long.222](https://aclanthology.org/2022.acl-long.222)

* Absolute evaluation study; English; 3 quality criteria; 1 dataset; 3 systems and 588 evaluation items per criterion; crowdsourced.

**Kasner & Dusek (2022)**:  Neural Pipeline for Zero-Shot Data-to-Text Generation:  [https://aclanthology.org/2022.acl-long.271](https://aclanthology.org/2022.acl-long.271)

* Absolute evaluation study; English; 5 quality criteria; 2 datasets; 6 systems and 600 evaluation items per dataset-criterion combination.

**Shardlow & Nawaz (2019)**:  Neural Text Simplification of Clinical Letters with a Domain Specific Phrase Table:  [https://aclanthology.org/P19-1037](https://aclanthology.org/P19-1037)

* Relative evaluation study; English; 1 quality criterion; 1 dataset; 4 systems and 100 evaluation items; crowdsourced.

**Castro Ferreira et al. (2018)**:  NeuralREG: An end-to-end approach to referring expression generation:  [https://aclanthology.org/P18-1182](https://aclanthology.org/P18-1182)

* Absolute evaluation study; English; 3 quality criteria; 1 dataset; 6 systems and 144 evaluation items per criterion; crowdsourced.

**Same et al. (2022)**:  Non-neural Models Matter: a Re-evaluation of Neural Referring Expression Generation Systems:  [https://aclanthology.org/2022.acl-long.380](https://aclanthology.org/2022.acl-long.380)

* Absolute evaluation study; English; 3 quality criteria; 2 datasets; varies between 6 and 8 systems and between 180 and 384 evaluation items per dataset-criterion combination; crowdsourced.

**Lin et al. (2022)**:  Other Roles Matter! Enhancing Role-Oriented Dialogue Summarization via Role Interactions:  [https://aclanthology.org/2022.acl-long.182](https://aclanthology.org/2022.acl-long.182)

* Absolute evaluation study; Chinese; 3 quality criteria; 1 dataset; 4 systems and 800 evaluation items per criterion.









## Track A and B Instructions

Step 1. Fill in the [registration form](https://docs.google.com/forms/d/e/1FAIpQLSetAzVp3BVkTaf8i0MZuya_sAKuP3ii6zC8wZVOCXTz392cEQ/viewform?usp=sharing), indicating which of the above papers, or which other paper(s), you wish to carry out a reproduction study for.

Step 2. After registration, the ReproNLP participants information will be made available to you, plus data, tools and other materials for each of the studies you have selected in the registration form.

Step 3. Carry out the reproduction, and submit a report of up to 8 pages plus references and supplementary material including a completed ReproGen Human Evaluation Sheet (HEDS) for each reproduction study, by April 1st 2024.

Step 4. The organisers will carry out light touch review of the evaluation reports according to the following criteria:

* Evaluation sheet has been completed.
* Exact repetition of study has been attempted and is described in the report.
* Report gives full details of the reproduction study, in accordance with the reporting guidelines provided.
* All tools and resources used in the study are publicly available.

Step 5. Present paper at the results meeting.

Reports will be included in the HumEval’24 proceedings, and results will be presented at the workshop in May 2024. Full details and instructions will be provided as part of the ReproNLP participants information.

## Important Dates

Report submission deadline: 1st of April 2024

Acceptance notification: 9th of April 2024

Camera-ready reports due: 19th of April 2024

Presentation of results: 21st of May 2024

All deadlines are 23:59 UTC-12.

## Organisers

Anya Belz, ADAPT/DCU, Ireland

Craig Thomson, University of Aberdeen, UK

Ehud Reiter, University of Aberdeen, UK

## Contact

anya.belz@adaptcentre.ie, c.thomson@abdn.ac.uk 

<https://repronlp.github.io>
