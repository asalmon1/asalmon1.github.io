---
layout: page
title: Projects
permalink: /projects/
---

**Fine-Tuning Generative AI on Error Messages** \| University College Dublin 

During Summer of 2024, I worked as a Student Researcher at University College Dublin. With the guidance of Assistant Professor Dr. Brett Becker, I began my research on enhanced error messages. I first completed a comprehensive literature review, focusing initially on general AI topics, and eventually narrowing down my research to the subject of enhanced programming error messages created by generative AI. I designed a study to determine if fine-tuning would improve the ability of GPT-3.5 to generate enhanced error messages, when provided with only the relevant code context. I then wrote a Python script to filter through a dataset of erroneous code files, removing unusable examples. I wrote example error messages for 40 of the selected code files, and then fine-tuned GPT-3.5 on these 40 code file and handwritten error message pairings. To complete my project, I compared the performance of the fine-tuned model to the performance of the base GPT-3.5 model on 60 additional erroneous code files.   

<img src="/images/D6CD4D88-F26C-4026-B209-B546BA5F31AF.jpg" alt="Final poster for the project">

Read my research paper <a href="https://drive.google.com/file/d/1_uS9JbR_WSkRSsOProIZ8-qxenqgLYem/view?usp=sharing">here</a>[^1].

<br>

**Introductory Assignment Sequence** \| UNC COMP 110 Teaching Assistant Team  

During my first semester as a TA for COMP 110, I collaborated with a partner to design a sequence of assignments for students in the Introduction to Programming course. The goal of these assignments was to progressively introduce students to concepts such as user input, `if`-`else` statements, `while` loops, and functions. Students built upon the first, very simple assignment by progressively implementing more complex concepts in the second and third assignments. This assignment sequence was used in class the following semester.   
View the first assignment [here](https://comp110-24s.github.io/exercises/simple-battleship.html), the second [here](https://comp110-24s.github.io/exercises/one-shot-battleship.html), and the third [here](https://comp110-24s.github.io/exercises/battleship.html).

<br>

**Predicting Adverse Health Events** \| Healthcare Analytics Data Institute

As part of a micro-internship with the Healthcare Data Analytics Institute, I created a predictive machine learning model to quantify the risk of mortality for a given patient, based on individual health data. In R, I performed exploratory data analysis to gain insights from provided data, ran feature selection to get rid of unrelated variables for model building, and ultimately generated a logistic regression model. I also used the ggplot package to generate histograms, box plots, etc, to visualize the data.   
View the project <a href="https://drive.google.com/file/d/1URVlZlsnvQLJY_19kqLToaXnvsSMPHrI/view?usp=sharing">here</a>.



[^1]: Note that the finished paper also includes another student's work on one-shot prompting for enhanced error messages. My research focused on the fine-tuned model.
