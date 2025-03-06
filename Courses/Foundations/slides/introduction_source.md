Foundations of learning from data
================
Omiros Papaspiliopoulos

# What this course is (and is not) about

---

"If it is written in Python, it's probably machine learning

If it is written in PowerPoint, it's probably AI"

(*Mat Velloso, Microsoft*) 

---

## My personal view on Data Science

- Provides “literacy” to empower people to understand and take decisions in a highly measurable world! 

- It is the Science between the human and the data


## The Data Science agenda

- Creating value from
- **Collecting, warehousing, curating**  
- Communicating
- Legislating about
- **Learning from ** 

Data!

## Learning from data

+ Prediction
+ Inference 
+ Causality
+ Uncertainty quantification

## Objectives of the course: Warehousing and curating

- Information retrieval and database management with `pandas`
- Transformations, non-numerical variables, long and wide data, good practices
- Dealing with missing and "weird"-looking data
- *Documentation* - this course created with **markdown** (also via Quarto)
   - Check out on *Aaron Swartz*

## Objectives of the course: Predictive modelling

- High-dimensional predictive regression models, shrinkage and selection
- Model selection (split-sample, bootstrap, information criteria, predictive vs structural learning)
- Classification
- Trees, forests, bagging and boosting

## Objectives of the course: Causal inference and uncertainty quantification

- Causal inference vs predictive modelling
- Foundations of causal inference
- Causal inference and high-dimensional regression
- Causal inference and trees
- Stability
- Prediction uncertainty quantification


# Course organisation and evaluation

## Structure

- Course organized along the three themes
- Main lectures by Om
  - Mix of Jupyter notebooks and slides
- Data challenges by Tommy
- A few TA sessions on basics by Pier
- All material is available here:
<https://datasciencebocconi.github.io/Courses/Foundations/>

## Expectations

- The course should work on multiple levels
- Depending on your background, previous exposure, and capacity in the material you should set your goals accordingly
  - Some will go very far into developing methods and understanding underlying theory
  - Others will learn sufficiently to use and slightly modify existing code but have a good intuition of the methods and their limitations
- You will work in groups of 3-5

## Evaluation

i. 9/31 exercises (group work)
ii. 13/31 data challenge  through the Bocconi Data Science Challenges Platform (group work)
iii. 9/31 exam (individual)
    - Multiple choice
    - Based on questions on basic knowledge and statistical challenges
    - Individualised data
    - Open book with laptops 



# Case studies

## Case study 1: IMDb dataset

![](https://datasciencebocconi.github.io/Images/text_mining/imdb.png)

## Case study 1: IMDb dataset

The Internet Movie Database ([IMDb](https://www.imdb.com)) is a popular
website for film reviews.

- Can we automatically identify the **sentiment** of a review?
- Can we predict the **IMDb rating** of a film, based on its reviews?

There are also a lot of practical problems:

- How do we **pre-process** and **clean** the data?
- How do we **convert words into numbers**?

## Case study 2: sales price prediction

<img
src="https://datasciencebocconi.github.io/Images/casestudy_housing/housesbanner.png"
style="width:100.0%" />

What is the right **price** for a **house** in Ames, Iowa?

In statistical terms: can you **predict** the final price based on the
characteristic of the house?

This is a **[Kaggle](https://www.kaggle.com)** playground competition.
You will be asked to join the competition along with other thousands of
players!

## Case study 3: the data challenge

<img
src="https://datasciencebocconi.github.io/Images/data_challenge/platform.png"
data-fig-align="center" />

The dataset will be disclosed at the kick-off date!

Your goal will be to construct a model which has good predictive
performance.

