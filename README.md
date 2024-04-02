# Estimation, machine learning and testing

## Content
* [Description](#description)
* [Learning Outcomes](#learning-outcomes)
* [Logistics](#logistics)
  + [Module Contacts](#module-contacts)
  + [Requirements](#requirements)
  + [Delivery of Module](#delivery-of-module)
  + [How the Technical Facilitator will deliver](#how-the-technical-facilitator-will-deliver)
  + [Expectations](#expectations)
* [Class Schedule](#class-schedule)
  + [Class Topics](#class-topics)
* [Grading Scheme](#grading-scheme)
* [Policies](#policies)
* [Resources](#resources)
  - [Documents](#documents)
  - [Simple Linear Regression](#simple-linear-regression)
  - [Multiple linear regression, interactions, qualitative predictors](#multiple-linear-regression-interactions-qualitative-predictors)
  - [Classification (logistic regression, generative models)](#classification-logistic-regression-generative-models)
  - [Resampling methods (CV, bootstrap) and Linear model selection and regularization](#resampling-methods-cv-bootstrap-and-linear-model-selection-and-regularization)
  - [Tree-based methods](#tree-based-methods)
  - [Support Vector Machines](#support-vector-machines)
  - [Survival Analysis, Principal Components Analysis, Ethics/Inequity/Reproducibility](#survival-analysis-principal-components-analysis-ethicsinequityreproducibility)
  + [How to get help](#how-to-get-help)
* [Folder Structure](#folder-structure)
* [Acknowledgements](#acknowledgements)

## Description
This module provides the intuition and skills required to design, implement, test and validate a variety of supervised learning models. We cover the basics of statistical learning including modelling with the goal of prediction versus inference, prediction accuracy and model interpretability trade-off, and the bias-variance trade-off. Each section of this module will cover a unique set of methods used for supervised learning on real data sets.

## Learning Outcomes
By the end of the module, students will:
1. Implement and interpret the results from several supervised learning approaches for regression and classification
2. Utilize resampling methods to extract more information from a data set and to choose the best model
3. Perform exploratory data analysis for unsupervised learning
4. Determine what is required for reproducible learning
5. Analyze the uncertainties associated with model results and the ethical consequences of acting on these results
6. Explain the different trade offs and considerations for the statistical methods in their toolkit to both technical and non-technical audiences

## Logistics

### Module Contacts
**Questions can be submitted to the #questions channel on Slack**

* Technical Facilitator: **{Name}** {Pronouns}. Emails to the Technical Facilitator can be sent to {first_name.last_name}@mail.utoronto.ca.
* Learning Support Staff: **{Name}** {Pronouns}. Emails to the Technical Facilitator can be sent to {first_name.last_name}@mail.utoronto.ca.

### Requirements
* Participants are not expected to have any coding experience, we designed the learning contents for beginners.
* Participants are encouraged to ask questions, and collaborate with others to enhance learning.
* Participants must have a computer and an internet connection to participate in online activities.
* Participants must have VSCode installed with the following extensions:
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
    * [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
* Participants must not use generative AI such as ChatGPT to generate code in order to complete assignments. It should be use as a supportive tool to seek out answers to questions you may have.
* We expect participants to have completed the [onboarding repo](https://github.com/UofT-DSI/Onboarding/tree/tech-onboarding-docs).
* Camera is optional although highly encouraged. We understand that not everyone may have the space at home to have the camera on.

### Delivery of Module
The module will run sychronously three times a week on Zoom. The first three days are used as "lectures" and will last a maximum of 3 hours. During this time, the Technical Facilitator will introduce the concepts for the week. The last day is used for as optional, asychronous work periods. The work periods will also last for up to 3 hours. During the work period, an Technical Facilitator or a Learning Support Staff will be present on Zoom to assist participants reach the intended learning outcomes.

### How the Technical Facilitator will deliver
The Technical Facilitators will introduce the concepts through a collaborative live coding session usiing the Python notebooks found under `/01_slides`. All Technical Facilitators will also upload any live coding files to this repository for any participants to revisit under `/live_code`.
 
### Expectations
Participants are encouraged to be active participants while coding and are encouraged to ask questions throughout the module.

## Class Schedule

### Class Topics

| Class  | Date   | Topic                                                 |  Resources | ISLP Chapter | DS: AFI Chapter |
|--------|--------|-------------------------------------------------------|------------| -------------|-----------------|
| 1      | TBD    | Key Concepts of Statistical Analysis                  | [Slides](./01_slides/1-statistical-learning.pdf)                      | 2 |  |
| 2      | TBD    | Simple linear regression                              | [Slides](./01_slides/2-linear-regression.pdf)                         | 3 | 8 |
| 3      | TBD    | Multiple linear regression, interactions and Qualitative Predictors  | [Slides](./01_slides/3-multiple-linear-regression.pdf) | 3 | 8 |        
| 4      | TBD    | Classification vs Regression                          | [Slides](./01_slides/4-classification.pdf)                            | 4 | 5 - 7 |
| 5      | TBD    | Classification (Logistic Regression)                | [Slides](./01_slides/5-logistic-regression.pdf)                       | 4 | 5 + 6 |
| 6      | TBD    | Classification (Generalized Linear Model)             | [Slides](./01_slides/6-generalized-linear-models.pdf)                 | 4 | 5 + 6 |  
| 7      | TBD    | Resampling Methods (Leave One Out Cross Validation)   |  [Slides](./01_slides/7-leave-one-out-cross-validation.pdf)           | 5 | 10 |
| 8      | TBD    | Resampling Methods (K-fold Cross Validation)          | [Slides](./01_slides/8-k-fold-cross-validation.pdf)                   | 5 | 10 |
| 9      | TBD    | Resampling Methods (Bootstrap)                        | [Slides](./01_slides/9-the-bootstrap.pdf)                             | 5 | 10 |                 

Alternative Textbook: [Data Science: A First Introduction](https://python.datasciencebook.ca/classification1.html) (Chapters 5-10)

## Grading Scheme

Grading is based on three components: 3 assignments, and class participation. The grading scheme is as follows:

| Assessment       | Number |  Individual Weight | Cumulative Weight
|------------------|--------|--------------------|------------------|
| Assignments      | 3      |  25%               | 75%              |
| Participation    | NA     |  NA                | 25%              |

**Assignments**

Assignments will cover key statistical concepts and related code implementation. The assignments are to complete according to the schedule below, for a total of 3 assignments. Assignments will be introduced in class, can be discussed in tutorial, and questions can be ask of the Technical Facilitator and/or Learning Support staff over email. Assignments are due by 11:59PM on the day they are due. Please arrange for extensions *in advance* with the Technical Facilitator or the TAs. Assignments should be submitted through the correct Google Forms link found below following the naming convention `firstname_lastname_a#`.

Assignments can be found in the `Assignments` directory, above. We've included an .html file (knitted Markdown file) for easy reading, as well as Jupyter Notebook files, that can be edited for submission. (To download files, click Raw > Save as.)

Note: If the assignment requires some content we end up not covering in class (i.e., we've fallen behind), it will be removed from the assignment / not be graded (you're welcome to submit answers if you like). Any questions that are removed will be determined and clearly indicated in the class before the assignment is due.

**Assignment Due-dates**

| Assessment        | Content         | Due Date                         | Submission Link |
| ------------------| ----------------|----------------------------------| ------------------ |
| Assignment 1      | Classes 1, 2, 3   |  TBD | Your Drive Folder |  
| Assignment 2      | Classes 4, 5, 6   |  TBD     | Your Drive Folder |
| Assignment 3      | Classes 7, 8, 9   |  TBD    | Your Drive Folder |

## Policies
* **Accessibility:** We want to provide an accessible learning environment for all. If there is something we can do to make this module more accessible to you, please let us know.
* **Module communications:** Communications take place over email or on Slack. If communicating over email, please include "DSI-EMT" or similar in the subject line, e.g. "DSI-EMT: stats question"
* **Camera:** Keeping your camera on is optional.
* **Microphone:** Please keep microphones muted unless you need to speak. Please indicate your name before speaking as some Zoom configurations make it hard to tell who is talking!
* **Assessment:** There will be homework which **is not** graded, but highly recommended, and there will be two assignments which **are** graded.

## Resources
Feel free to use the following as resources:

### Documents
- [Cheatsheet](./06_additional_resources/02_assignments/05_review_session_material/dsi-emlt-cheat-sheet-2.pdf)
- [Cross Validation - Basic Idea and Steps](./06_additional_resources/05_review_session_material/cross-validation-basic-idea-and-steps.pdf)
- [EMLT Tutorial](./06_additional_resources/05_review_session_material/emlt-tutorials.pdf)
- [ISLP Labs](https://islp.readthedocs.io/en/latest/installation.html)

### Videos 
- [ISLP Playlist](https://www.youtube.com/playlist?list=PLoROMvodv4rPP6braWoRt5UCXYZ71GZIQ)

#### Simple Linear Regression
- [Linear Regression, explained in 2 minutes](https://www.youtube.com/watch?v=CtsRRUddV2s)
- [Linear Regression, Clearly Explained!!!](https://www.youtube.com/watch?v=7ArmBVF2dCs&pp=ygUic2ltcGxlIGxpbmVhciByZWdyZXNzaW9uIHN0YXRxdWVzdA%3D%3D)

#### Multiple linear regression, interactions, qualitative predictors
- [Multiple Regression, Clearly Explained!!!](https://www.youtube.com/watch?v=EkAQAi3a4js&pp=ygUic2ltcGxlIGxpbmVhciByZWdyZXNzaW9uIHN0YXRxdWVzdA%3D%3D)

#### Classification (logistic regression, generative models)
- [Logistic Regression, explained in 3 minutes](https://www.youtube.com/watch?v=EKm0spFxFG4)
- [StatQuest: Logistic Regression](https://www.youtube.com/watch?v=yIYKR4sgzI8&list=PLblh5JKOoLUKxzEP5HA2d-Li7IJkHfXSe)
- [StatQuest: Linear Discriminant Analysis (LDA) clearly explained.](https://www.youtube.com/watch?v=azXCzI57Yfc&pp=ygUNTERBIHN0YXRxdWVzdA%3D%3D)
- [StatQuest: K-nearest neighbors, Clearly Explained](https://www.youtube.com/watch?v=HVXime0nQeI&pp=ygUNa25uIHN0YXRxdWVzdA%3D%3D)
- [Naive Bayes, Clearly Explained!!!](https://www.youtube.com/watch?v=O2L2Uv9pdDA&pp=ygUaYmF5ZXMgY2xhc3NpZmllciBzdGF0cXVlc3Q%3D)
- [Generalized Linear Model](https://www.youtube.com/watch?v=SqN-qlQOM5A)

#### Resampling methods (CV, bootstrap) and Linear model selection and regularization
- [Linear Modelling](https://www.youtube.com/watch?v=-inJu1jHqb8)
- [Machine Learning Fundamentals: Cross Validation](https://www.youtube.com/watch?v=fSytzGwwBVw&pp=ygUYdmFsaWRhdGlvbiBzZXQgc3RhdHF1ZXN0)
- [Bootstrapping Main Ideas!!!](https://www.youtube.com/watch?v=Xz0x-8-cgaQ&pp=ygUXYm9vdHN0cmFwcGluZyBzdGF0cXVlc3Q%3D)
- [Bootstrapping Method](https://www.youtube.com/watch?v=uGsf3spCM3Y)
- [$k$-fold Cross Validation](https://www.youtube.com/watch?v=TIgfjmp-4BA)

### How to get help
![image](/steps_to_ask_for_help.png)

<hr>

## Folder Structure

```markdown
.
├── 01_slides
├── 02_assignments
├── 03_exercises
├── 04_homework
├── 05_instructors
├── 06_additional_resources
├── LICENSE
├── README.md
├── requirements.txt
└── steps_to_ask_for_help.png
```

* **slides:** module slides as interactive notebooks (.ipynb files)
* **pdf slides:** module slides as PDF files
* **live_coding:** Notebooks from class live coding sessions
* **exercises:** Work to be done alongside the lectures
* **homework:** Optional homework to practice concepts covered in class
* **assignments:** Graded assignments
* **additional resources:** Extra material not covered by the module
* **instructors:** Instructions for the Technical Facilitator on what to teach
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the Technical Facilitator


## Acknowledgements
Rohan Alexander supervised the development of this module. The first slides were developed by Simone Collier. Slides have been created and modified by Navona Calarco and Julia Gallucci for Winter 2023. Materials were re-developed from R to Python by Inessa De Angelis in Fall 2023. This module draws extensively on *An Introduction to Statistical Learning with Applications in R* (2nd edition, 2021), by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani and *An Introduction to Statistical Learning with Applications in Python* (2023) by Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani, and Jonathan Taylor. The structure of the repos were heavily organized and modified by Vishnou Vinayagame and Daniel Razavi in Winter of 2024.
