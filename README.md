# SuperLearner Guide

A guide to using SuperLearner for prediction. This is now included as a [vignette in the SuperLearner package](https://cran.r-project.org/web/packages/SuperLearner/vignettes/Guide-to-SuperLearner.html).

## [SuperLearner Intro](https://github.com/ck37/superlearner-guide/blob/master/SuperLearner-Intro.Rmd)

* Installing
* Background
* Create dataset
* Review available models
* Fit single models
* Fit ensemble
* Predict on new dataset
* Customize a model setting
* External cross-validation
* Test multiple hyperparameter settings
* Parallelize across CPUs
* Distribution of ensemble weights
* Feature selection (screening)
* Optimize for AUC
* XGBoost hyperparameter exploration

## Intermediate

(To be created)

* create.Learner() custom environments
* SL.caret wrapper
* Custom learner wrapper
* Custom screener
* Library analysis - cumulative
* Library analysis - individual algorithms
* Recombine SuperLearner

## Advanced

(To be created)

* Parallelize across computers (SLURM)
* Repeated cross-validation
* Data-adaptive V-selection for cross-validation
* Multi-level meta-learning

## Resources

Books:

* Intro to Statistical Learning [(free pdf)](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf) [(Amazon page)](https://smile.amazon.com/Introduction-Statistical-Learning-Applications-Statistics-ebook/dp/B01IBM7790/) by Gareth James et al.
* [Applied Predictive Modeling](https://smile.amazon.com/Applied-Predictive-Modeling-Max-Kuhn-ebook/dp/B00K15TZU0/) by Max Kuhn
* Elements of Statistical Learning
* Many others

Campus Groups:

* D-Lab's [Machine Learning Working Group](http://dlab.berkeley.edu/working-groups/machine-learning-working-group)
* D-Lab's [Cloud Computing Working Group](http://dlab.berkeley.edu/working-groups/cloud-computing-working-group)
* [The Hacker Within](http://www.thehackerwithin.org/berkeley/) / [Berkeley Institute for Data Science](https://bids.berkeley.edu/)

Courses at Berkeley:

* Stat 154 - Statistical Learning
* CS 189 / CS 289A - Machine Learning
* PH 252D  - Causal Inference
* PH 295 - Big Data
* PH 295 - Targeted Learning for Biomedical Big Data
* INFO - TBD

Also many Coursera offerings and other online classes.

## References

Erin LeDell, Maya L. Petersen & Mark J. van der Laan, "Computationally Efficient Confidence Intervals for Cross-validated Area Under the ROC Curve Estimates." (Electronic Journal of Statistics)

Polley EC, van der Laan MJ (2010) Super Learner in Prediction. U.C. Berkeley Division of Biostatistics Working Paper Series. Paper 226. http://biostats.bepress.com/ucbbiostat/paper266/

van der Laan, M. J., Polley, E. C., & Hubbard, A. E. (2007). Super learner. Statistical applications in genetics and molecular biology, 6(1).

van der Laan, M. J., & Rose, S. (2011). Targeted learning: causal inference for observational and experimental data. Springer Science & Business Media.
