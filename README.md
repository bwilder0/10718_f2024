# 10718: Machine Learning in Practice
Instructor: Bryan Wilder (bwilder@andrew.cmu.edu)


This is a project-based course designed to provide students training and experience in solving real-world problems using machine learning, exploring the interface between research and practice. The goal of this course is to give students exposure to the nuance of applying machine learning to the real-world, where common assumptions (like iid and stationarity) break down. Students will learn how to formulate real-world business or policy scenarios as machine learning problems, how to address common challenges which arise in applying ML to such problems (e.g., distribution shift or missingness), and how to rigorously evaluate the results of such interventions in practice. We will place an emphasis throughout on issues related to ethics and fairness in machine learning, and discuss how choices throughout the machine learning pipeline – including problem formulation, outcome definition, data collection, and model training – contribute to the social impact of algorithmic systems.

[Syllabus](https://docs.google.com/document/d/1XWFsySUTZ2KEmXP57mnIzEkh9QV8qokQtreRBm6-cNg/edit?usp=sharing)

[Shared google drive](https://drive.google.com/drive/folders/1bhFtUAe4eMx1Wjl7u4BfBLXhbJy2oPJ8?usp=drive_link)

## Course Components

The requirements of this course consist of two components: participating in in-class discussions and completing the course project. 

### Class discussions
This course emphasizes the process of thinking through real-world problems and how and when they can be addressed using machine learning. Accordingly, our class sessions will rely on student participation to discuss potential scenarios and case studies together. You are highly encouraged to engage actively during class discussions, which will make the course much more exciting for everyone. During such discussions, we expect you to be respectful at all times towards your fellow students. 

Discussions will loosely follow the [role-playing seminar](https://colinraffel.com/blog/role-playing-seminar.html) format; for each paper, you will either be assigned a presenter role or complete the non-presenter assignment (described below).

**Presenter assignment**: You will periodically present a paper in class, taking on one of the following presenter roles.
* Educator: Explain the key ideas in the paper to the class. Keep your presentation to 5-10 minutes maximum.
* Investigator: Investigate one of the paper’s authors. What is their area of expertise? Where have they worked previously? What prior projects might have led to working on this one? Explore what motivated them to write the paper and what biases they may have.
* Reviewer: Discuss both one strength and one weakness of the paper. What did you like about the paper? Do you agree with the paper's stance/findings? Did the paper overlook anything? Is there something that could have strengthened the work?
* Discussion Leader: Prepare three discussion questions to ask the class, and lead the discussion amongst the students when answering these questions.

**Non-presenter assignment**: If you are not presenting the paper, you must still read the paper and provide at least one discussion question about the paper (e.g., something you're uncertain about or would like to hear discussed).

[Signup sheet for discussions](https://docs.google.com/spreadsheets/d/1JA-ip54RfVxH2N5P6MBBnCdhsoxkS3gJ7QyoaLauOQQ/edit?usp=sharing)

### Course project

Students will complete a semester-long course project that explores the application of machine learning to a problem of practical interest. Students may work in groups of up to three people. Each group will select a dataset, which _cannot_ be one commonly used in machine learning research. Over a series of assignments, each group will define a problem to be addressed using the dataset, clean and explore it, develop baselines and machine learning models, and explore the impact of additional desiderata on their pipeline (e.g., fairness, privacy, interpretability, or model efficiency). Students can either select their own dataset for the project (which cannot be a commonly used ML benchmark dataset) or select one from the set of examples provided.  

[Example datasets for project](https://docs.google.com/document/d/1K8Yd82q4S-aWpBXdmG9w1FRJonpKrUI0Hxw7_HFL5yc/edit?usp=sharing)

## Grading 

Each component will contribute towards the final grade as follows:

**Discussion participation** (40%), graded out of 30 points
* Presenter assignments: 3 over the course of the semester, 5 points each. 15 total points
* Non-presenter assignments: 15 over the course of the semester (out of 16 possible sessions), 1 point each
* You are allowed to miss one non-presenter assignment without penalty.
* This format may be adjusted as needed during the semester.

**Course project** (60%), graded out of 100 points
* Assignment 0: 5 points
* Assignment 1: 20 points
* Assignment 2: 20 points
* Assignment 3: 20 points
* Assignment 4: 20 points
* Final presentation: 15 points


## Course Schedule


| Week | Dates       | Topic                         | Required reading                                                                                                                                                                                                                                                                                  | Assignments due  |
| ---- | ----------- | ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| 1    | Mon: Aug 26 | Class Intro and Overview      |                                                                                                                                                                                                                                                                                                   |                  |
| 1    | Wed: Aug 28 | ML Project Scoping            |                                                                                                                                                                                                                                                                                                   |                  |
| 2    | Mon: Sep 2  | Class cancelled: labor day    |                                                                                                                                                                                                                                                                                                   |                  |
| 2    | Wed: Sep 4  | State of ML                   | [Artificial Intelligence—The Revolution Hasn’t Happened Yet<br>](https://hdsr.mitpress.mit.edu/pub/wot7mkc1/release/10)[The bitter lesson<br>](http://www.incompleteideas.net/IncIdeas/BitterLesson.html?ref=blog.heim.xyz)[The secrets of machine learning](https://arxiv.org/abs/1906.01998)    |                  |
| 3    | Mon: Sep 9  | Problem formulation           | [Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations](https://www.science.org/doi/10.1126/science.aax2342)                                                                                                                                                            | Assignment 0 due |
| 3    | Wed: Sep 11 | Data & feature engineering    | [Pervasive Label Errors in Test Sets Destabilize Machine Learning Benchmarks<br>](https://arxiv.org/abs/2103.14749)[Can Foundation Models Wrangle Your Data?](https://arxiv.org/abs/2205.09911)                                                                                                   |                  |
| 4    | Mon: Sep 16 | Model Selection Methodology   | [External Validation of a Widely Implemented Proprietary Sepsis Prediction Model in Hospitalized Patients<br>](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2781307)[Difficult Lessons on Social Prediction from Wisconsin Public Schools](https://arxiv.org/abs/2304.06205) |                  |
| 4    | Wed: Sep 18 | Project check-ins             |                                                                                                                                                                                                                                                                                                   | |
| 5    | Mon: Sep 23 | Hyperparameter tuning         | [Optimizer Benchmarking Needs to Account for Hyperparameter Tuning<br>](https://arxiv.org/abs/1910.11758)[On the Difficulty of Evaluating Baselines: A Study on Recommender Systems](https://arxiv.org/abs/1905.01395)                                                                            |    Assignment 1 due               |
| 5    | Wed: Sep 25 | Distribution shift 1          | [The Effect of Natural Distribution Shift on Question Answering Models<br>](https://arxiv.org/abs/2004.14444)[On the Need of a Modeling Language for Distribution Shifts: Illustrations on Tabular Datasets](https://arxiv.org/abs/2307.05284)                                                    |                  |
| 6    | Mon: Sep 30 | Distribution shift 2          | [The Data Addition Dilemma<br>](https://www.arxiv.org/abs/2408.04154)[Reliable and Trustworthy Machine Learning for Health Using Dataset Shift Detection](https://arxiv.org/abs/2110.14019)                                                                                                       |                  |
| 6    | Wed: Oct 2  | Privacy                       | [The Secret Sharer<br>](https://www.usenix.org/system/files/sec19-carlini.pdf)[Considerations for Differentially Private Learning with Large-Scale Public Pretraining](https://arxiv.org/abs/2212.06470)                                                                                          |                  |
| 7    | Mon: Oct 7  | Project pitches               |                                                                                                                                                                                                                                                                                                   | Assignment 2 due |
| 7    | Wed: Oct 9  | Project pitches               |                                                                                                                                                                                                                                                                                                   |                  |
| 8    | Mon: Oct 14 | No Class - Mid-semester break |                                                                                                                                                                                                                                                                                                   |                  |
| 8    | Wed: Oct 16 | No Class - Mid-semester break |                                                                                                                                                                                                                                                                                                   |                  |
| 9    | Mon: Oct 21 | Interpretability              | ["Why Should I Trust You?": Explaining the Predictions of Any Classifier<br>](https://arxiv.org/abs/1602.04938)[Interpretable Machine Learning: Moving from Mythos to Diagnostics](https://arxiv.org/abs/2103.06254)                                                                              |                  |
| 9    | Wed: Oct 23 | Fairness                      | [Designing equitable algorithms<br>](https://www.nature.com/articles/s43588-023-00485-4)[Measuring Implicit Bias in Explicitly Unbiased Large Language Models](https://arxiv.org/abs/2402.04105)                                                                                                  |                  |
| 10   | Mon: Oct 28 | Safety and manipulability     | [Jailbroken: How Does LLM Safety Training Fail?<br>](https://arxiv.org/abs/2307.02483)[Open Problems and Fundamental Limitations of Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2307.15217)                                                                                                                                                                                                                |                  |
| 10   | Wed: Oct 30 | Class cancelled               |                                                                                                                                                                                                                                                                                                   |                  |
| 11   | Mon: Nov 4  | Model compression             | [Model Compression in Practice<br>](https://arxiv.org/abs/2310.04621)[Lost in Pruning: The Effects of Pruning Neural Networks beyond Test Accuracy](https://arxiv.org/abs/2103.03014)                                                                                                             |                  |
| 11   | Wed: Nov 6  | Uncertainty quantification    | [Uncertainty Sets for Image Classifiers using Conformal Prediction<br>](https://arxiv.org/abs/2009.14193)[Evaluating the Utility of Conformal Prediction Sets for AI-Advised Image Labeling](https://arxiv.org/abs/2401.08876)                                                                    |                  |
| 12   | Mon: Nov 11 | Causality                     | [The Seven Tools of Causal Inference, with Reflections on Machine Learning](https://dl.acm.org/doi/10.1145/3241036)                                                                                                                                                                               | Assignment 3 due |
| 12   | Wed: Nov 13 | ML and intervention           | [Reimagining the machine learning life cycle to improve educational outcomes of students<br>](https://www.pnas.org/doi/full/10.1073/pnas.2204781120)[Predicting and Preventing Gun Violence: An Experimental Evaluation of READI Chicago](https://academic.oup.com/qje/article/139/1/1/7220727)   |                  |
| 13   | Mon: Nov 18 | ML and intervention 2         | [Machine Learning Who to Nudge: Causal vs Predictive Targeting in a Field Experiment on Student Financial Aid Renewal<br>](https://arxiv.org/abs/2310.08672)[The Relative Value of Prediction in Algorithmic Decision Making](https://arxiv.org/abs/2312.08511)                                   |                  |
| 13   | Wed: Nov 20 | Guest lecture: Pim Welle (Allegheny County Human Services Department)                 |                                                                                                                                                                                                                                                                                                   |                  |
| 14   | Mon: Nov 25 | Performativity                        | [Performative Prediction<br>](https://arxiv.org/abs/2002.06673)[Training Machine Learning to Anticipate Manipulation](https://dan.bjorkegren.com/manipulation.pdf)                                                                                                                                                                                      |                  |
| 14   | Wed: Nov 27 | No class                |                                                                                                                                                                   |                  |
| 15   | Mon: Dec 2  | Project presentations         |                                                                                                                                                                                                                                                                                                   | Assignment 4 due |
| 15   | Wed: Dec 4  | Project presentations         |                                                                                                                                                                                                                                                                                                   |
