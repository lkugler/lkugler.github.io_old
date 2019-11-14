---
layout: page
title: Master's thesis
permalink: /mthesis/
---

### The added value of machine-learning methods in forecasting wind turbine icing
#### Abstract

Icing events at wind turbines in elevated areas (above 600 m altitude) cause unplanned downtimes and significant costs. The Austrian research initiative ICE CONTROL aims to improve icing forecasts which are commonly provided by applying a decision criterion of Temperature and Humidity on numerical weather forecasts or physical icing models to classify whether or not there will be blade icing in a certain time interval. Given that observations exist, simple statistical tools like logistic regression can provide calibrated probabilities.
In this study, the added value of using machine-learning (ML) methods over simple statistical tools shall be quantified. Incorporating ensemble forecasts and latest observations may lead to a significant forecast improvement by providing additional information over a single deterministic run. However, it is not clear that ML supersedes simpler models because turbine icing is a rare event and more complex models generally need more data, especially if trained on noisy data due to forecast errors of numerical weather prediction models. The algorithms to be studied include support vector machines and decision trees (implemented in the python package *scikit-learn*), generalized additive models (*pyGAM*) and artificial neural nets (*keras*).
[PDF Abstract](https://homepage.univie.ac.at/a1254888/MA-pres1-abstract.pdf)


### Resources
- First presentation in the Master's seminar (Slides in German: [PDF](https://homepage.univie.ac.at/a1254888/MA-pres1.pdf), [PPTX](https://homepage.univie.ac.at/a1254888/MA-pres1.pptx))
- Second presentation in the Master's seminar (Slides in German: [PDF](https://homepage.univie.ac.at/a1254888/MA-pres2.pdf), [PPTX](https://homepage.univie.ac.at/a1254888/MA-pres2.pptx))


#### Introduction to Machine Learning

| [Prof. Yaser's Machine Learning Course - CS 156, provided by Caltech](https://www.youtube.com/playlist?list=PLD63A284B7615313A) |     <a href="https://www.youtube.com/playlist?list=PLD63A284B7615313A"><img src="https://i.ytimg.com/vi/FIbVs5GbBlQ/hqdefault.jpg?sqp=-oaymwEXCNACELwBSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLCABp2TWr57I6xQmDuu4-1cQF6MAg" alt="Animation" height="100"/></a> |
| Breiman, L., and Coauthors, 2001: Statistical modeling: The two cultures (with comments and a rejoinder by the author). Statistical science, 16 (3), 199–231. |


#### Machine Learning Literature

| Friedman, J., Hastie, T., & Tibshirani, R. (2009). The elements of statistical learning (Vol. 2). New York, NY, USA:: Springer series in statistics. |
| Hsieh, W. W. (2009). Machine learning methods in the environmental sciences: Neural networks and kernels. Cambridge university press. |
| [Vapnik, V. (1992). Principles of risk minimization for learning theory. In Advances in neural information processing systems (pp. 831-838)](http://papers.nips.cc/paper/506-principles-of-risk-minimization-for-learning-theory.pdf) |
| Vapnik, V. N., 1999: An overview of statistical learning theory. IEEE transactions on neural networks, 10 (5), 988–999. |

