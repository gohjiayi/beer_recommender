# Building a Beer Recommender using Bandit Algorithms
This project strives to build a beer recommender using both collaborative filtering and bandit algorithm, and subsequently evaluate the best performing technique.

## Project Resources
For more project details, please refer to the following resources linked here:
1. [Project Report](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/gohjiayi/beer_recommender/master/docs/Beer_Recommender_Report.pdf)
2. [Project Slides](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/gohjiayi/beer_recommender/master/docs/Beer_Recommender_Slides.pdf)
3. [Project Video](https://youtu.be/jZ1umEd4Jtg)

## Project Directory Structure
```
├── data
│   ├── bandit
│   │   ├── simulate_[bandit_algo].csv
│   │   └── ...
│   ├── beer_matrix_100.csv
│   └── beer_reviews.csv
├── eda.ipnyb
├── data_preprocessing.ipnyb
├── collaborative_filtering.ipnyb
├── bandit_algorithms.ipynb
└── ...
```

Note:
- All files within in `data/` are accessible [here](https://drive.google.com/drive/folders/1J5YIv4fQVaSdlERP14393stlqFvhM_mj?usp=sharing); more details on the source will be further elaborated.
- All .ipnyb notebooks are tuned for Google Colab usage. For local usage, minor code changes and environment setup will be required.

## 1. Data Gathering
Download the BeerAdvocate Beer Reviews dataset from data.world linked [here](https://data.world/socialmediadata/beeradvocate) and save it as `data/beer_reviews.csv`.

## 2. Exploratory Data Analysis
Run `eda.ipnyb` to gain insights from the dataset collected.

## 3. Data Preprocessing
Run `data_preprocessing.ipnyb` to preprocess the Beer Reviews dataset, which generates `data/beer_matrix_100.csv`. This data subset will be specifically used to build a recommender system using Bandit Algorithms.

## 4. Collaborative Filtering
Run `collaborative_filtering.ipnyb` to build a recommender system using Collaborative Filtering methods.

## 5. Bandit Algorithms
Run `bandit_algorithms.ipnyb` to build recommender systems using Bandit Algorithms - Epsilon-Decay, Annealing Softmax, UCB1, Bayesian UCB and Thompson Sampling. Simulated data for each algorithm will be generated as `data/bandit/simulate_[bandit_algo].csv`.

## Contributors
- Chan Cheah Cha - [@cheahcha](https://github.com/cheahcha)
- Chua Kai Bing - [@kaibinggg](https://github.com/kaibinggg)
- Goh Jia Yi - [@gohjiayi](https://github.com/gohjiayi)
- Lim Jia Qi - [@addflag](https://github.com/addflag)
- Tan Zen Wei - [@zenweiii](https://github.com/zenweiii)
