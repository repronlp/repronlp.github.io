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

# ReproNLP 2023

# First Call for Participation

## Background

Across Natural Language Processing (NLP), a growing body of work is exploring the issue of reproducibility in machine learning contexts. The field is currently far from having a generally agreed tool box of methods for defining and assessing reproducibility. Reproducibility of results of human evaluation experiments is particularly under-addressed which is of concern for areas of NLP where human evaluation is common including e.g. MT, text generation and summarisation. More generally, human evaluations provide the benchmarks against which automatic evaluation methods are assessed across NLP.

We previously organised the First ReproGen Shared Task on reproducibility of human evaluations in NLG as part of Generation Challenges (GenChal) at INLG’21, and the Second ReproGen Shared Task at INLG’22, where we extended the scope to encompass automatic evaluation methods as well as human. This year we are expanding the scope of the shared task series to encompass all NLP tasks, renaming it the ReproNLP Shared Task on Reproducibility of Evaluations in NLP. This year we are focussing on human evaluations, and the results session will be held at the 3rd Workshop on Human Evaluation of NLP Systems (HumEval 2023). 

As with the ReproGen shared tasks, our overall aim is (i) to shed light on the extent to which past NLP evaluations have been reproducible, and (ii) to draw conclusions regarding how NLP evaluations can be designed and reported to increase reproducibility. If the task is run over several years, we hope to be able to document an overall increase in levels of reproducibility over time.

## About ReproNLP

ReproNLP has three tracks, one an ‘unshared task’ in which teams attempt to reproduce their own prior evaluation results (Track B below), the others standard shared tasks in which teams repeat existing evaluation studies with the aim of reproducing their results (Tracks A and C):

**A. Legacy Reproducibility Track** (papers see below): For a shared set of selected evaluation studies from ReproGen 2022 (see below), participants repeat one or more of the studies, and attempt to reproduce their results. As in ReproGen, participants will be given additional information and resources (beyond what is in the published papers) about experimental details by the ReproNLP organisers.

**B. RYO Track**: Reproduce Your Own previous evaluation results, and report what happened. Unshared task.

**C. ReproHum Track** (papers see below): For a shared set of selected evaluation studies from the ReproHum Project, participants repeat one or more of the studies, and attempt to reproduce their results, using information provided by the ReproNLP organisers only, and following a common reproduction approach.

## Track A Papers

We have selected the papers listed below for inclusion in ReproNLP Track A (these are the same papers as in Track A in ReproGen 2022). The authors have agreed to evaluation studies from their papers as identified below being used for Track A, and have provided the system outputs to be evaluated and any reusable tools that were used in the original evaluations. We also have available completed ReproGen Human Evaluation Sheets which we will use as the standard for establishing similarity between different human evaluation studies.

The papers and studies, with many thanks to the authors for supporting ReproGen, are:

**van der Lee et al. (2017)**: PASS: A Dutch data-to-text system for soccer, targeted towards specific audiences: <https://www.aclweb.org/anthology/W17-3513.pdf> [1 evaluation study; Dutch; 20 evaluators; 1 quality criterion; reproduction target: primary scores]

**Dušek et al. (2018)**: Findings of the E2E NLG Challenge: <https://www.aclweb.org/anthology/W18-6539.pdf> [1 human evaluation study; English; MTurk; 2 quality criteria; reproduction target: primary scores]

**Qader et al. (2018)**: Generation of Company descriptions using concept-to-text and text-to-text deep models: dataset collection and systems evaluation: <https://www.aclweb.org/anthology/W18-6532.pdf> [1 human evaluation study; English; 19 evaluators; 4 quality criteria; reproduction target: primary scores]

**Santhanam & Shaikh (2019)**: Towards Best Experiment Design for Evaluating Dialogue System Output: <https://www.aclweb.org/anthology/W19-8610.pdf> [3 evaluation studies differing in experimental design; English; 40 evaluators; 2 quality criteria; reproduction target: correlation scores between 3 studies]

**Nisioi et al. (2017)**: Exploring Neural Text Simplification Models: <https://aclanthology.org/P17-2014.pdf> [one automatic evaluation study; reproduction target: two automatic scores]; [one human evaluation study; 70 sentences; 9 system outputs; 4 quality criteria; reproduction target: primary scores]

## Track C Papers

The specific experiments listed and described below are currently the subject of reproduction studies in the ReproHum project. The authors have agreed to us using them in ReproNLP and have provided very detailed information about the experiments. In some cases we have introduced standardisations to the experimental design as noted in the detailed instructions to participants which will be shared upon registration. 

The papers and studies, with many thanks to the authors for supporting ReproHum and ReproNLP, are:

**Vamvas & Sennrich (2022)**:  As Little as Possible, as Much as Necessary: Detecting Over and Undertranslations with Contrastive Conditioning:  <https://aclanthology.org/2022.acl-short.53.pdf> [1 human evalution study (of 2 in paper); English to German; 2 evaluators; 1 quality criteria; 1 system; approx. 800 outputs; reproduction target:  primary scores]

**Lin et al. (2022)**:  Other Roles Matter! Enhancing Role-Oriented Dialogue Summarization via Role Interactions:  <https://aclanthology.org/2022.acl-long.182.pdf> [1 human evaluation study; Chinese; 3 evaluators; 3 quality criteria; 200 outputs per system; 4 systems; reproduction target: primary scores]

**Lux & Vu (2022)**:  Language-Agnostic Meta-Learning for Low-Resource Text-to-Speech with Articulatory Features:  <https://aclanthology.org/2022.acl-long.472.pdf>  [1 human evaluation; German; Student evaluators (34 responses); 1 quality criterion; 12 outputs per system; 2 systems; reproduction target:  primary scores]

**Chakrabarty et al. (2022)**:  It's not Rocket Science: Interpreting Figurative Language in Narratives:  <https://aclanthology.org/2022.tacl-1.34.pdf>  [2 human evaluation studies (of 4 in paper);  English;  MTurk; 1 quality criterion; 25 outputs per system, 5/8 systems (varies between idiom and simile studies); reproduction target:  primary scores]

**Puduppully & Lapata (2021)**:  Data-to-text Generation with Macro Planning:  <https://aclanthology.org/2021.tacl-1.31.pdf>  [first human evaluation (relative); English; MTurk; 2 quality criteria; 20 outputs per system; 5 systems, reproduction target: primary scores] [second human evaluation (absolute); English; MTurk; 3 quality criteria; 80 outputs per system; 5 systems; reproduction target: primary scores]

## Track A, B and C Instructions

Step 1. Fill in the registration form at <https://forms.gle/dnf73tH3jcyBEBCX6>, indicating which of the above papers, or which of your own papers, you wish to carry out a reproduction study for.

Step 2. After registration, the ReproNLP participants information will be made available to you, plus data, tools and other materials for each of the studies you have selected in the registration form.

Step 3. Carry out the reproduction, and submit a report of up to 8 pages plus references and supplementary material including a completed ReproGen Human Evaluation Sheet (HEDS) for each reproduction study, by 4 August 2023.

Step 4. The organisers will carry out light touch review of the evaluation reports according to the following criteria:

* Evaluation sheet has been completed.
* Exact repetition of study has been attempted and is described in the report.
* Report gives full details of the reproduction study, in accordance with the reporting guidelines provided.
* All tools and resources used in the study are publicly available.

Step 5. Present paper at the results meeting.

Reports will be included in the HumEval’23 proceedings, and results will be presented at the workshop in September 2023. Full details and instructions will be provided as part of the ReproNLP participants information.

## Important Dates

Report submission deadline: 4 August 2023

Acceptance notification: 18 August 2023

Camera-ready reports: 25 August 2023

Workshop camera-ready proceedings ready: 31 August 2023

Presentation of results: 7 or 8 September 2023

All deadlines are 23:59 UTC-12.

## Organisers

Anya Belz, ADAPT/DCU, Ireland

Craig Thomson, University of Aberdeen, UK

Ehud Reiter, University of Aberdeen, UK

## Contact

anya.belz@adaptcentre.ie, c.thomson@abdn.ac.uk 

<https://repronlp.github.io>
