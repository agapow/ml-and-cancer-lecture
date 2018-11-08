---
author:
- Paul Agapow (p.agapow@imperial.ac.uk)
institute: Data Science Institute, Imperial College London
title: Machien Learning and Cancer
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
* Something to do with AI and Big Data ...


# What is Machine Learning & AI & Big Data ...?

Blurred by hype, marketing, sloppy language and technological progress.

::: notes

* Once clear
* Now blurred by hype, marketing, sloppy language and technological progress.


# What is Big Data?

:::::::::::::: {.columns}
::: {.column width="30%"}
Data too 'big' to be handled by current approaches
:::
::: {.column width="30%"}
* Velocity
* Volume
* Variety
* *Veracity*
* *Value*
:::
::: {.column width="30%"}
Any large rich dataset
:::
::::::::::::::

::: notes

* When Big Data was first coined, there was a clear definition: data that was too 'big' (in a broad sense) for us to work with in the ways we were used to
* The ways in which it was 'too big' were captured as the 3 Vs, later 4 and finally 5. (Although 'value' has always seemed dubious.)
* This definition is fragile to progress: once upon a time, a megabyte of data was a lot and you might have has trouble loading it into an analysis program. Now it isn't a problem.
* Due to this and loose language, in practice *Big Data* now tends to  means:
  - large-ish datasets
  - that are rich (contain multiple types of data)
  - and dirty (need processing & cleaning)
  - obtained from realworld sources
  - which could be a sample of a potentially 'Big' dataset (e.g. the kidney patients in a given hospital vs. all the patients in the UK)


# What is Artificial Intelligence

In practice:

* ~~a field of scientific research~~
* ~~machine learning~~
* ~~neural networks~~
* ~~deep learning~~
* making a computational system that duplicates / emulates / replaces a human
  - usually involving applied statistical optmization, machine learning
* more of an objective than a methodology

::: notes

* AI is a

:::


# What is Machine Learning?

picture


# What is Machine Learning?

|              | Statistical   | Machine        |
|--------------|:-------------:|:--------------:|
| Assumptions  | strong        | weak           |
| Data         | small         | large          |
| Solutions    | "the best"    | "good enough"  |
| Hypothesis   | proof         | exploration    |


Stuff under the insertsubtitle


# What is Machine Learning?

- **Train** a **model** from data
- This model transforms **input** data into useful **outputs**
  - Continuous outputs (e.g. real numbers) are **regressions**
  - Categorical / discrete outputs are **classications**
- The model in some way encapsulates or **generalizes** the data


# Dinner

- Eat spaghetti
- Drink wine
- do stuff


![picture of spaghetti](images/spaghetti.jpg)

# Going to sleep

- Get in bed
- Count sheep
