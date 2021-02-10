# NBA All Star Predictions
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

## Overview
A quick Jupyter notebook I threw together to make some predictions about the 2021 NBA All Star game. 

Scrapes NBA individual typical + advanced statistics and all star lists from publicly available sources and uses these as an input for: 
 - Logistic Regression
 - Decision Trees
 - Random Forest
 - Support Vector Machine
 - Multi-Layer Perception Classifier
 
 Performs some basic analysis to help determine which statistics are correlated. I also tried some basic over/under sampling techniques to no avail.

## Getting Started 
If you want to play around with the NBA data I've aggregated or the methods I've used for aggregation, that's awesome!

### Prerequisites
* Anaconda
* Jupyter
* numpy
* pandas
* Sklearn
* Imblearn (not mandatory, used for resampling tests)

### Installation 
1. Clone the repo 
 ```sh
   git clone https://github.com/rudiejd/NBA_AllStar_Predictions.git
   ```
2. Open the notebook in Jupyter 
3. If you want to check my outputs, just look at the latest output cells. Note that re-running the same models on your machine may change results due to the stochaistic nature of these models. 
4. If you'd like to modify the methodology or suggest a new model/algorithm for testing, [make an issue](https://github.com/rudiejd/NBA_AllStar_Predictions/issues/new) and I will address it A.S.A.P.

 ## Results
 I included the results from each model in the predictions folder. You can find accuracy statistics in the included Jupyter notebook.


[contributors-shield]: https://img.shields.io/github/contributors/rudiejd/NBA_AllStar_Predictions.svg?style=for-the-badge
[contributors-url]: https://github.com/rudiejd/NBA_AllStar_Predictions/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/rudiejd/NBA_AllStar_Predictions.svg?style=for-the-badge
[forks-url]: https://github.com/rudiejd/NBA_AllStar_Predictions/network/members
[stars-shield]: https://img.shields.io/github/stars/rudiejd/NBA_AllStar_Predictions.svg?style=for-the-badge
[stars-url]: https://github.com/rudiejd/NBA_AllStar_Predictions/stargazers
[issues-shield]: https://img.shields.io/github/issues/rudiejd/NBA_AllStar_Predictions.svg?style=for-the-badge
[issues-url]: https://github.com/rudiejd/NBA_AllStar_Predictions/issues
[license-shield]: https://img.shields.io/github/license/rudiejd/NBA_AllStar_Predictions.svg?style=for-the-badge
[license-url]: https://github.com/rudiejd/NBA_AllStar_Predictions/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/jdrudie
[product-screenshot]: images/screenshot.png
