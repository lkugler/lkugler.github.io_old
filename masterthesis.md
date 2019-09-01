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

#### Literature

| Davis, N., Hahmann, A. N., Clausen, N-E., & Zagar, M. (2014). [Icing Impacts on Wind Energy Production.](http://orbit.dtu.dk/en/publications/icing-impacts-on-wind-energy-production(8dfa9669-5ac8-4997-bed4-aeeaae3b7061).html) DTU Wind Energy. | Introduces the IceBlade physical icing model, includes a bit of statistical postprocessing |
| Zhang, L., K. Liu, Y. Wang, and Z. Omariba, 2018: Ice detection model of wind turbine blades based on random
forest classifier. Energies, 11 (10), 2548. | . |
| Niu, D., Liang, Y., Wang, H., Wang, M., & Hong, W. C. (2017). Icing Forecasting of Transmission Lines with a Modified Back Propagation Neural Network-Support Vector Machine-Extreme Learning Machine with Kernel (BPNN-SVM-KELM) Based on the Variance-Covariance Weight Determination Method. Energies, 10(8), 1196. |


#### Machine Learning in Meteorology (examples)

| Rasp, S., and S. Lerch, 2018: Neural networks for postprocessing ensemble weather forecasts. Monthly Weather Review, 146, doi:10.1175/MWR-D-18-0187.1. |
| Rasp, S., M. S. Pritchard, and P. Gentine, 2018: Deep learning to represent subgrid processes in climate models. Proceedings of the National Academy of Sciences, 115, 201810 286, doi:10.1073/pnas.1810286115. |

#### Introduction to Machine Learning

| [Prof. Yaser's Machine Learning Course - CS 156, provided by Caltech](https://www.youtube.com/playlist?list=PLD63A284B7615313A) |     <a href="https://www.youtube.com/playlist?list=PLD63A284B7615313A"><img src="https://i.ytimg.com/vi/FIbVs5GbBlQ/hqdefault.jpg?sqp=-oaymwEXCNACELwBSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLCABp2TWr57I6xQmDuu4-1cQF6MAg" alt="Animation" height="100"/></a> |
| Breiman, L., and Coauthors, 2001: Statistical modeling: The two cultures (with comments and a rejoinder by the author). Statistical science, 16 (3), 199–231. |


#### Machine Learning Literature

| Friedman, J., Hastie, T., & Tibshirani, R. (2009). The elements of statistical learning (Vol. 2). New York, NY, USA:: Springer series in statistics. |
| Hsieh, W. W. (2009). Machine learning methods in the environmental sciences: Neural networks and kernels. Cambridge university press. |
| [Vapnik, V. (1992). Principles of risk minimization for learning theory. In Advances in neural information processing systems (pp. 831-838)](http://papers.nips.cc/paper/506-principles-of-risk-minimization-for-learning-theory.pdf) |
| Vapnik, V. N., 1999: An overview of statistical learning theory. IEEE transactions on neural networks, 10 (5), 988–999. |
| [Proof: The RBF Kernel as mapping into an infinite dimensional feature space](http://pages.cs.wisc.edu/~matthewb/pages/notes/pdf/svms/RBFKernel.pdf) |
| Smola, A. J., and B. Schölkopf, 2004: A tutorial on support vector regression. Statistics and computing, 14 (3), 199–222. |
