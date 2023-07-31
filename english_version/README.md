# Project-2. Research of HR agency data using statistical tests in the context of EDA.

## Contents
[1. Project Description](https://github.com/Axewyl/HR-Agency-Research/english_version/blob/master/README.md#Project-Description)

[2. What case are we solving?](https://github.com/Axewyl/HR-Agency-Research/english_version/blob/master/README.md#What-case-are-we-solving)

[3. Brief information about the data](https://github.com/Axewyl/HR-Agency-Research/english_version/blob/master/README.md#Brief-information-about-the-data)

[4. Stages of work on the project](https://github.com/Axewyl/HR-Agency-Research/english_version/blob/master/README.md#Stages-of-work-on-the-project)

[5. Result](https://github.com/Axewyl/HR-Agency-Research/english_version/blob/master/README.md#Results)

[6. Authors](https://github.com/Axewyl/HR-Agency-Research/english_version/blob/master/README.md#Authors)

[7. Conclusions](https://github.com/Axewyl/HR-Agency-Research/english_version/blob/master/README.md#Conclusions)

### Project Description
*HR*-the agency studies trends in the labor market in *IT*. The company wants to conduct a study based on data on salaries in the field of *Data Science* for 2020-2022 and get some conclusions.

Original dataset: [“Data Science Job Salaries” (kaggle.com)](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)

### What case are we solving
- We are carefully studying the details of the task.
- Let's get acquainted with the additional theoretical material that is given before the task.
- We will use tips and hints when executing the project.
- We will answer all the security questions.
- We will upload the laptop with our solution to *GitHub*, having designed it in accordance with the requirements of *PEP8*.
- We submit the project for verification and draw conclusions on intelligence analysis.

**Task description:**
1. Find out what factors affect the salary of a specialist *Data Scientist*.
2. As well as answer the key questions of the HR agency:
- Is there an annual increase in salaries for *Data Scientist* specialists?
- How do the salaries of *Data Scientist* and *Data Engineer* compare in 2022?
- How do the salaries of *Data Scientist* specialists in companies of various sizes compare?
- Is there a connection between the presence of positions *Data Scientist* and *Data Engineer* and the size of the company?
3. Answer additional questions:
- Is there a dependence of the salary level of a specialist *Data Scientist* depending on work experience (position held)?
- Is there a dependence of wages on the type of remoteness of work?

**Quality metric**
In order to answer the questions, we build graphs. Thus, we make the primary conclusion of the influence of this feature on dependence. Next, we conduct statistical testing to finally confirm or refute the hypothesis.
The choice of the test depends on a number of factors:
- What type of attribute does it have.
- How many groups are being compared.
- Groups are dependent or not.
- The attribute is distributed according to the normal law or not.

**What we practice**
- Learning how to perform data preprocessing;
- explore the primary information;
- build graphs and draw primary conclusions for further research;
- to put forward hypotheses and select the necessary testing;
- make informed conclusions based on statistical testing.

### Brief information about the data
Background information [здесь](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries).

### Stages of work on the project
1. Familiarity with the data;
2. Preliminary data analysis;
3. Data preprocessing and cleaning;
4. Plotting;
5. Formulation of hypotheses;
6. Statistical testing;
7. Conclusions.

### Results
The result is the level of statistical significance (*p-value*) for each question. Based on it, we accept or reject the hypothesis.

### Authors
- [Andrey](https://t.me/Axewyl)

### Conclusions
**Basic research:**
- There is no annual salary growth for *Data Scientist* specialists.
- The salaries of *Data Scientist* and *Data Engineer* in 2022 are statistically equal.
- The size of the company affects the salary of *Data Scientist* and *Data Engineer*.
- There is not enough data to establish a connection between the presence of positions *Data Scientist* and *Data Engineer* and the size of the company.

**Additional research:**
- The *experience_level* attribute affects the PO *Data Scientist*.
- The *remote_ratio* attribute affects the PO *Data Scientist*, this is confirmed both graphically and statistically.

:arrow_up:[Contents](https://github.com/Axewyl/HR-Agency-Research/english_version/blob/master/README.md#Contents)

