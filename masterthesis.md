---
layout: page
title: Master's thesis
permalink: /mthesis/
---

### The Added Value of Machine Learning in Forecasting Wind Turbine Icing

<img src="https://www.researchgate.net/profile/Lukas_Kugler/publication/338015101/figure/fig14/AS:837478109962250@1576681749723/The-expense-matrix-assigns-cost-C-to-true-positive-TP-and-false-positive-FP_W640.jpg" alt="Image Expense Matrix"
width="300" />

![Image PEV Gain](https://github.com/lkugler/lkugler.github.io/raw/master/_data/mthes1.jpg)

#### Abstract

Icing events at wind turbines in elevated areas cause unexpected outages in power production and significant costs. More accurate forecasts would improve power production predictability and could partially reduce downtimes. Thus, advanced post-processing by machine-learning methods is applied to obtain probabilistic forecasts. The quality and improvement by using advanced methods is estimated in terms of the forecasts’ discrimination, calibration and economic value. The results confirm that the proposed machine-learning methods significantly outperform empirical & logistic classification approaches for customers with relatively high cost-loss ratios.

The idea for this thesis originates from the Austrian research initiative ICE CONTROL which aims to improve icing forecasts that are commonly obtained by applying an empirical decision criterion on temperature and humidity from numerical weather forecasts. Another approach is to drive physical icing models from numerical weather prediction (NWP) models to classify whether or not there will be rotor blade icing within a certain time interval. Finally, as soon as in-situ observations exist, simple statistical tools like logistic regression can provide calibrated probabilities. Logistic regression, however, is not able to model the intrinsic multiplicative structure of icing, where multiple factors must be present at the same time to a sufficient extent to produce icing.

In this study, the added value of using machine-learning (ML) methods over simple statistical tools was quantified. Despite of ML models’ higher complexity, it is not clear for them to su- persede simpler models because the studied events are quite rare with occurrence rates between 5 and 25 % leading to class imbalance problems, as well as a possible lack of samples with data of only two winter seasons.

The evaluation included logistic regression, generalized additive models (GAM), support vector machines (SVM), decision trees and artificial neural networks. The NWP input data was taken from the Weather Research and Forecasting Model (WRF) which was run specifically for this project in a 2-domain configuration that downscales ECMWF’s IFS model from 12.5 km to a 2.5 km resolution inner nest.

The verification was conducted using measurements that were taken directly on the nacelle of a wind turbine at a wind farm near Ellern, Germany. Three different classes of icing were used as predictand: Meteorological icing, defined by atmospheric temperature and dewpoint spread; Instrumental icing, defined by a visual classification of camera images that detects icing on the turbine; and lastly the Visible accretion which describes times with increasing amounts of ice on the turbine as seen by the camera.



### Resources
- First presentation in the Master's seminar (Slides in German: [PDF](https://github.com/lkugler/lkugler.github.io/raw/master/_data/MA-pres1.pdf), [PPTX](https://github.com/lkugler/lkugler.github.io/raw/master/_data/MA-pres1.pptx))
- Second presentation in the Master's seminar (Slides in German: [PDF](https://github.com/lkugler/lkugler.github.io/raw/master/_data/MA-pres2.pdf), [PPTX](https://github.com/lkugler/lkugler.github.io/raw/master/_data/MA-pres2.pptx))
- pre-work abstract [[PDF]](https://github.com/lkugler/lkugler.github.io/raw/master/_data/MA-pres1-abstract.pdf)
- Full Text [[HTML/PDF]](https://www.researchgate.net/publication/338015101_The_Added_Value_of_Machine_Learning_in_Forecasting_Wind_Turbine_Icing)


#### Introduction to Machine Learning

| [Prof. Yaser's Machine Learning Course - CS 156, provided by Caltech](https://www.youtube.com/playlist?list=PLD63A284B7615313A) |
| Breiman, L., and Coauthors, 2001: Statistical modeling: The two cultures (with comments and a rejoinder by the author). Statistical science, 16 (3), 199–231. |


#### Machine Learning Literature

| Friedman, J., Hastie, T., & Tibshirani, R. (2009). The elements of statistical learning (Vol. 2). New York, NY, USA:: Springer series in statistics. |
| Hsieh, W. W. (2009). Machine learning methods in the environmental sciences: Neural networks and kernels. Cambridge university press. |
| [Vapnik, V. (1992). Principles of risk minimization for learning theory. In Advances in neural information processing systems (pp. 831-838)](http://papers.nips.cc/paper/506-principles-of-risk-minimization-for-learning-theory.pdf) |
| Vapnik, V. N., 1999: An overview of statistical learning theory. IEEE transactions on neural networks, 10 (5), 988–999. |

