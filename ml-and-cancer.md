---
author:
- Paul Agapow (p.agapow@imperial.ac.uk)
institute: Data Science Institute, Imperial College London
title: Machine Learning and Cancer
subtitle: Using Big Data for insight and prediction
date: 2018/11/14

...

# What is Machine Learning?

* "a field of Artificial Intelligence"
* "(the science of) getting computers to learn and act like humans do"
* "getting computers to act without being explicitly programmed"
* "computer systems that automatically improve with experience"
* "using statistical techniques to give computer systems the ability to learn"
* "neural networks"
* something to do with AI and Big Data ...


# What is Machine Learning (& AI & Big Data ...)?


:::::::::::::: {.columns}
::: {.column width="40%"}




Necessary vocabulary blurred by:

* indistinct terms
* hype & marketing
* sloppy language
* technological progress
* new names for old concepts

:::
::: {.column width="40%"}

![WikiMedia Commons](images/ai-hype.jpg)

:::
::::::::::::::


::: notes

* Terms once seemed to be clear, in practice anyway
* Now blurred
* Some never strictly defined
* Some have an operational or functional definition now superseded by progress
* Let's give you an intuitive feels for terms

:::


# What is Big Data?

Data *too extreme* to be handled by current approaches.

Extreme in what way?

* Velocity
* Volume
* Variety
* ... Veracity
* ... ... Value

Practically, any large rich dataset.


::: notes

* When first coined, there was a clear definition: data that was too 'big' (in a broad sense) for us to work with in the ways we were used to
* Ways in which data can be 'too big': the 3 Vs, later 4 then 5.
* (Although 'value' has always seemed dubious.)
* This definition is fragile to progress:
  - Once upon a time, a megabyte of data was a lot and you might have had trouble loading it into an analysis program.
* In practice *Big Data* now tends to mean datasets that are:
  - large-ish (or could be large)
  - rich (contain multiple types of data)
  - complex (lots of relationships)
  - dirty (need lots of processing & cleaning)
  - real world (as opposed to experimental)

:::


# What is Artificial Intelligence

In practice:

* ~~a field of scientific research~~
* ~~machine learning~~
* ~~neural networks~~
* ~~deep learning~~
* more of an objective than a methodology
* computational systems that duplicates / emulates / replaces human effort
* usually involving applied statistical optmization or machine learning

![Ray Kurweil *The Singularity is Near*](images/only-humans.png)

::: notes

* Again a gap between formal and actual language
* There is certainly AI research and AI science but that that is not what headlines are talking about
* Generally, you don't solve or analyse problems 'using AI'
* There's no real 'AI' methodology, just methods that achieve AI

:::


# What is Machine Learning?

:::::::::::::: {.columns}
::: {.column width="40%"}
contents...
:::
::: {.column width="60%"}
contents...
:::
::::::::::::::

::: notes

* ML overlaps with traditional statistical analysis
* Deep learning (broadly neural networks) is a type of representational learning
* Representational learning is a type of learning
* AI broadly means ML, towards the deep learning end

:::


# What is Machine Learning?

|                  | **Statistical**   | **Machine**    |
|------------------|:-----------------:|:--------------:|
| **Assumptions**  | strong            | weak           |
| **Data**         | small             | large          |
| **Optimize by**  | fitting           | training       |
| **Solutions**    | "the best"        | "good enough"  |
| **Hypothesis**   | proof             | exploration    |
| **Test**         | p-values etc.     | validation     |


::: notes

* Another way to look at ML is how it is used
* ML models use relatively little prior knowledge or specifications
  - few preconceptions about how to solve this problem
  - as a consequence, need a lot of data
  - as a further consequence, ML is less about 'the' solution or 'the best' solution and more 'a solution'
  - more absolute sucess than absolute
  - hence how it's used: recommendation systems, diagnosis from radiographs, anomaly detection

:::


# What is Machine Learning?

* **Train** a **model** from data
* The model in some way encapsulates or **generalizes** the data
* This model transforms **features** into **labels**
  - Continuous outputs (e.g. real numbers) are **regressions**
  - Discrete outputs (e.g. categories) are **classifications**
* Arguably 'non-parametric'


::: notes

* Another way to look at ML is what it does
* Some regard regressions and other traditional methods as ML
* ML has it's own language
  - train: learn from
  - features: input data, covariates
  - weights: parameters
  - labels: output data, dependent variables

:::


# Machine learning: practical example


![Korou et al.](images/ml-in-cancer-prognosis-paper.jpg)

* Cancer is disease of many subtypes
* Vital to classify cases & forecast path


# Why now?

ML has come of age due to:

* Enough data
* Enough compute
* Technical progress
* Need 'good enough' solutions


# Going to sleep

Two of the most widely adopted machine learning methods are supervised learning and unsupervised learning – but there are also other methods of machine learning. Here's an overview of the most popular types.

Supervised learning algorithms are trained using labeled examples, such as an input where the desired output is known. For example, a piece of equipment could have data points labeled either “F” (failed) or “R” (runs). The learning algorithm receives a set of inputs along with the corresponding correct outputs, and the algorithm learns by comparing its actual output with correct outputs to find errors. It then modifies the model accordingly. Through methods like classification, regression, prediction and gradient boosting, supervised learning uses patterns to predict the values of the label on additional unlabeled data. Supervised learning is commonly used in applications where historical data predicts likely future events. For example, it can anticipate when credit card transactions are likely to be fraudulent or which insurance customer is likely to file a claim.

Unsupervised learning is used against data that has no historical labels. The system is not told the "right answer." The algorithm must figure out what is being shown. The goal is to explore the data and find some structure within. Unsupervised learning works well on transactional data. For example, it can identify segments of customers with similar attributes who can then be treated similarly in marketing campaigns. Or it can find the main attributes that separate customer segments from each other. Popular techniques include self-organizing maps, nearest-neighbor mapping, k-means clustering and singular value decomposition. These algorithms are also used to segment text topics, recommend items and identify data outliers.

Semisupervised learning is used for the same applications as supervised learning. But it uses both labeled and unlabeled data for training – typically a small amount of labeled data with a large amount of unlabeled data (because unlabeled data is less expensive and takes less effort to acquire). This type of learning can be used with methods such as classification, regression and prediction. Semisupervised learning is useful when the cost associated with labeling is too high to allow for a fully labeled training process. Early examples of this include identifying a person's face on a web cam.

Reinforcement learning is often used for robotics, gaming and navigation. With reinforcement learning, the algorithm discovers through trial and error which actions yield the greatest rewards. This type of learning has three primary components: the agent (the learner or decision maker), the environment (everything the agent interacts with) and actions (what the agent can do). The objective is for the agent to choose actions that maximize the expected reward over a given amount of time. The agent will reach the goal much faster by following a good policy. So the goal in reinforcement learning is to learn the best policy.
