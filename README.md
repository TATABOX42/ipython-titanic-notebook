# Machine Learning tutorial: Predicting Titanic passenger survival 

This tutorial is [adapted from](https://www.kaggle.com/omarelgabry/titanic/a-journey-through-titanic) and was modified by [MSc. Benjamin Tovar](https://www.linkedin.com/in/benjamintovarcis/) on November 2015.

## Introduction

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

[Source](https://www.kaggle.com/c/titanic)

## Data structure and description

```
    survival        Survival
                    (0 = No; 1 = Yes)
    pclass          Passenger Class
                    (1 = 1st; 2 = 2nd; 3 = 3rd)
    name            Name
    sex             Sex
    age             Age
    sibsp           Number of Siblings/Spouses Aboard
    parch           Number of Parents/Children Aboard
    ticket          Ticket Number
    fare            Passenger Fare
    cabin           Cabin
    embarked        Port of Embarkation
                    (C = Cherbourg; Q = Queenstown; S = Southampton)
    SPECIAL NOTES:
    Pclass is a proxy for socio-economic status (SES)
    1st ~ Upper; 2nd ~ Middle; 3rd ~ Lower
```

## Tutorial Goals

The tutorial serves as an introduction to the [Scikit-learn Machine Learning Python awesome library](http://scikit-learn.org/stable/index.html)

### Awesome tutorials and more information:

[Tutorial: Machine Learning for Astronomy with Scikit-learn](http://www.astroml.org/sklearn_tutorial)