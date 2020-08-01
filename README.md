# 10718, 94889: Machine Learning for Public Policy Lab
### Fall 2020: Tues & Thurs, 3:20-4:40pm, Remote

This is a project-based course designed to provide students training and experience in solving real-world problems using machine learning, with a focus on problems from public policy and social good.

Through lectures, discussions, readings, and project assignments, students will learn about and experience building end-to-end machine learning systems, starting from project definition and scoping, through modeling, to field validation and turning their analysis into action. Through the course, students will develop skills in problem formulation, working with messy data, communicating about machine learning with non-technical stakeholders, model interpretability, understanding and mitigating algorithmic bias & disparities, and evaluating the impact of deployed models.

**Pre-Requisites**: Students will be expected to know Python, and have prior coursework in machine learning methods. Experience with SQL, *nix command line, git(hub), and working on remote machines will be helpful.

**[DRAFT SYLLABUS](/syllabus.pdf)**

## People

### Instructors

| Rayid Ghani | Kit Rodolfa |
| --- | --- |
| <img src='http://www.datasciencepublicpolicy.org/wp-content/uploads/2018/05/RayidGhani-012-400x400.jpg' width='200' height='200' /> <br /> GHC 8023 <br /> Office Hours: <br />  TBD | <img src='/kit_rodolfa.png' /> <br /> GHC 8018 <br /> Office Hours: TBD |

### Teaching Assistants
| Sebastian Caldas | Himil Sheth |
| --- | --- |
| <img src='https://www.ml.cmu.edu/images/caldas-sebastian-500-min.jpg' width='200' height='200' /> <br /> Office Hours: <br /> Tue 10-11am <br /> Wed 10-11am <br /> in GHC 8009 | <img src='/himil.jpg' width='200' height='200' /> <br /> Office Hours: <br /> Mon 2:00-3:00pm <br /> Thu 4:30-5:30pm <br /> GHC 8th Floor, by printers |

## Tentative Schedule

See the **[draft syllabus](/syllabus.pdf)** for much more detail as well, including information about group projects, grading, and helpful optional readings.

|  **Week** | **Dates&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;** | **Holidays?** | **Lecture/Discussion&nbsp;Topic&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;** | **Project&nbsp;Activity&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;** | **Goal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;** | **Required&nbsp;Readings&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;** | **Deliverable**&nbsp;/&nbsp;Expected&nbsp;Output&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
|  1 | Tu: Jan 14<br/>Th: Jan 16 |  | Tu: Intro/Overview + Project Overviews<br/>Th: Scoping, Problem Definition, Balancing goals (equity, efficiency, effectiveness) | Intro/Overview | Get familiar with the class, goals, and understand project choices | Thursday:<br/>• [Data Science Project Scoping Guide](http://www.datasciencepublicpolicy.org/home/resources/data-science-project-scoping-guide/)<br/>• [Using Machine Learning to Assess the Risk of and Prevent Water Main Breaks](https://dl.acm.org/citation.cfm?id=3219835) |  |
|  2 | Tu: Jan 21<br/>Th: Jan 23 |  | Tu: Case Studies + Discussion<br/>Th: Acquiring Data, Privacy, Record Linkage | Project Definition & Data Discovery | Data Audit and Exploration<br/><br/>TA Sessions: SQL, Databases, github | Tuesday:<br/>• [Fine-grained dengue forecasting using telephone triage services](https://nyunetworks.github.io/Pubs/rehman-science16.pdf)<br/>• [Predictive Modeling for Public Health: Preventing Childhood Lead Poisoning](http://www.dssgfellowship.org/wp-content/uploads/2016/01/p2039-potash.pdf)<br/>• [What Happens When an Algorithm Cuts Your Health Care](https://www.theverge.com/2018/3/21/17144260/healthcare-medicaid-algorithm-arkansas-cerebral-palsy) | Beginning of week, team and project assignments |
|  3 | Tu: Jan 28<br/>Th: Jan 30 |  | Tu: Data Exploration<br/>Th: Building ML Pipelines |  | Finalize Project Scope and Data Stories | Tuesday:<br/>• TBD reading on data exploration<br/>• [Practical Statistics for Data Scientists, Chapter 1](https://learning.oreilly.com/library/view/practical-statistics-for/9781491952955/ch01.html#EDA)<br/><br/>Thursday:<br/>• [Architecting a Machine Learning Pipeline](https://towardsdatascience.com/architecting-a-machine-learning-pipeline-a847f094d1c7) | ETL of some dataset (census?)<br/>Data exploration<br/>Scope refinement |
|  4 | Tu: Feb 4<br/>Th: Feb 6 |  | Analytical Formulation / Baselines |  | Initial Data Science Pipeline Setup and Mockups<br/>(problem formulation and validation process) | Tuesday:<br/>• [Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations](https://science.sciencemag.org/content/sci/366/6464/447.full.pdf)<br/>• [Always Start with a Stupid Model, No Exceptions](https://blog.insightdatascience.com/always-start-with-a-stupid-model-no-exceptions-3a22314b9aaa) | *First week of deep dives*<br/>**Project Scope + Proposal with Descriptive Statistics** |
|  5 | Tu: Feb 11<br/>Th: Feb 13 |  | Feature Engineering / Imputation | Code Pipeline Development | Iteration 1 - Build End to End Code Pipeline <br/>(Focus on end-to-end shell) | Tuesday:<br/>• TBD Feature Development Case Study<br/>• [Missing Data Conundrum](https://medium.com/ibm-data-science-experience/missing-data-conundrum-exploration-and-imputation-techniques-9f40abe0fd87) | Skeleton Code (Pipeline), Mockups<br/>**Proposal Peer Reviews** |
|  6 | Tu: Feb 18<br/>Th: Feb 20 |  | Performance Metrics / Evaluation Pt. I (splits, metrics) |  |  | Tuesday:<br/>• [Cross-validation strategies for data with temporal, spatial, hierarchical, or phylogenetic structure](https://onlinelibrary.wiley.com/doi/pdf/10.1111/ecog.02881)<br/>• [The Secrets of Machine Learning](https://arxiv.org/abs/1906.01998) | **Technical Modeling Plan** (features, label definition(s), model specifications, etc) |
|  7 | Tu: Feb 25<br/>Th: Feb 27 | (Feb 24 drop deadline) | Performance Metrics / Evaluation Pt. II (audition) |  | Iteration 2 - End to End Code Pipeline<br/>(Focus on feature development) | Tuesday:<br/>• [Evaluating and Comparing Classifiers](https://link.springer.com/chapter/10.1007/978-3-319-59162-9_2)<br/>• [Transductive Optimization of Top k Precision](https://arxiv.org/abs/1510.05976) | Code (Pipeline), Initial Models (and analysis) |
|  8 | Tu: Mar 3<br/>Th: Mar 5 |  | Overfitting, Leakage, Issues in Deployment |  |  | Tuesday:<br/>• [Three Pitfalls to Avoid in Machine Learning](https://www.nature.com/magazine-assets/d41586-019-02307-y/d41586-019-02307-y.pdf)<br/>• [Leakage in Data Mining](https://www.researchgate.net/profile/Claudia_Perlich/publication/221653692_Leakage_in_Data_Mining_Formulation_Detection_and_Avoidance/links/54418bb80cf2a6a049a5a0ca/Leakage-in-Data-Mining-Formulation-Detection-and-Avoidance.pdf)<br/>• [Why is Machine Learning Deployment Hard?](https://towardsdatascience.com/why-is-machine-learning-deployment-hard-443af67493cd) | Early Results: Correct but Crappy |
|  9 | Tu: Mar 17<br/>Th: Mar 19 | (prev wk spring brk) | Model Interpretability Pt. I: global + postmodeling |  | Iteration 3 - End to End Code Pipeline <br/>(Focus on evaluation, results and intial front-end demo) | Tuesday:<br/>• [Interpretable Classification Models for Recidivism Prediction](https://rss.onlinelibrary.wiley.com/doi/pdf/10.1111/rssa.12227)<br/>• [Intelligible Models for HealthCare: Predicting Pneumonia Risk and Hospital 30-day Readmission](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.704.9327&rep=rep1&type=pdf) | **Refined Feature List** |
|  10 | Tu: Mar 24<br/>Th: Mar 26 |  | Model Interpretability Pt. II: local |  |  | Tuesday:<br/>• [Why Should I Trust You? Explaining the Predictions of any Classifier](https://dl.acm.org/doi/abs/10.1145/2939672.2939778)<br/>• [Model Agnostic Supervised Local Explanations](http://papers.nips.cc/paper/7518-model-agnostic-supervised-local-explanations)<br/>• [Explainable machine-learning predictions for the prevention of hypoxaemia during surgery](https://www.nature.com/articles/s41551-018-0304-0.pdf) | Model Interpretation |
|  11 | Tu: Mar 31<br/>Th: Apr 2 |  | Bias and Fairness Pt I |  |  | Tuesday:<br/>• [Fairness Definitions Explained](https://dl.acm.org/citation.cfm?doid=3194770.3194776)<br/>• [A Theory of Justice, pages 1-19](https://blogs.baruch.cuny.edu/eng2100kmwd/files/2015/12/A-Theory-of-Justice-Excerpts.pdf)<br/>• [Racial Equity in Algorithmic Criminal Justice](https://heinonline.org/HOL/Page?handle=hein.journals/duklr68&id=1067&div=33&collection=journals) [Focus on sections: I.B.2, all of section II, III introduction, III.B, and III.D.3] | Results (across models, features, metrics)<br/>Add bias analysis methods |
|  12 | Tu: Apr 7<br/>Th: Apr 9 |  | Bias and Fairness Pt II | Model selection, evaluation, balancing efficiency and equity | Final model choice and understanding its performance and impact on disparities | Tuesday:<br/>• [A case study of algorithm-assisted decision making in child maltreatment hotline screening decisions](http://proceedings.mlr.press/v81/chouldechova18a/chouldechova18a.pdf)<br/>• [Equality of Opportunity in Supervised Learning](http://papers.nips.cc/paper/6373-equality-of-opportunity-in-supervised-learning)<br/>• [Classification with fairness constraints: A meta-algorithm with provable guarantees](https://dl.acm.org/citation.cfm?doid=3287560.3287586) | **Draft Research Proposal Section** |
|  13 | Tu: Apr 14<br/>Th: Apr 16 | Apr 16 | Causality and Field Validation |  |  | Tuesday:<br/>• [The seven tools of causal inference, with reflections on machine learning](https://ftp.cs.ucla.edu/pub/stat_ser/r481.pdf)<br/>• TBD Field Trial Case Study | *No deep dive - Thursday off* |
|  14 | Tu: Apr 21<br/>Th: Apr 23 |  | Analysis to Action, Accountability and Transparency | Communications & Transition Planning | Project Report and Presentations<br/>Field Trial Design | Tuesday:<br/>• [Ethics and Data Science, entire book](https://learning.oreilly.com/library/view/ethics-and-data/9781492043898/)<br/>• [Communicating Data with Tableau, Chapter 1](https://learning.oreilly.com/library/view/communicating-data-with/9781449372019/)<br/>• [Teaching Statistics: A Bag of Tricks, Chapter 11](https://www.oxfordscholarship.com/view/10.1093/oso/9780198785699.001.0001/oso-9780198785699-chapter-11) | *Last week of deep dives*<br/>**Draft Field Trial Design Section** |
|  15 | Tu: Apr 28<br/>Th: Apr 30 |  | Final Presentations | Presentations |  |  | **Presentation** |
|  16 | May 7 | (Finals Wk) |  | Final Report Due | Final Report |  | **Report and Repo and Code Documentation** |
