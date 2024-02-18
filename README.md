
# Movie Industry Analysis


An in-depth analysis of the movie industry, exploring genres, release patterns, and revenue factors.


## Table of Contents
- [Business Understanding](#business-understanding)
- [Data Understanding](#data-understanding)
- [Data Preparation](#data-preparation)
- [Data Limitations](#data-limitations)
- [Data Analysis](#data-analysis)
- [Code Quality](#code-quality)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Business Understanding
* Major firms are producing a growing amount of original content for the entertainment industry, especially in the movie business. Seeing this trend, Microsoft has made the decision to open a new film studio and enter the film industry. But because Microsoft lacks experience in the film business, it needs to know what kinds of movies are currently doing well on the box office. With the purpose of assisting Microsoft in making profitable content decisions, this project aims to investigate and evaluate the landscape of popular movies.


This project aims to provide valuable insights to Microsoft's new movie studio by:

Identifying the most successful genres in terms of box office performance.
Analyzing the correlation between production budget and box office success.
Offering recommendations on the types of films that are likely to perform well, guiding strategic decisions for Microsoft's entry into the movie industry.

## Data Understanding
* Data Souces
The dataset used in this analysis was obtained by combining multiple datasets from popular movie review websites like www.themoviedb.org and www.the-numbers.com k]. It contains information on various movies, including their genres, popularity, vote averages, production budgets, and box office performance. The data source provides a comprehensive view of the movie landscape, making it suitable for our analysis.
* Data Properties
The dataset comprises key features like [genre, popularity, production budgets and movie sales] that are crucial for understanding the factors influencing a movie's success. These properties align with our real-world problem as we seek to identify patterns in successful films and guide Microsoft's decision-making in the movie industry.
## Data Preparation
In order to be able to use my dataset I had to prepare & clean it first. This involved removing missing values, removing duplicates and dropping unnecessary columns from my datasets before I could merge them and get my final dataset.
## Data Limitations
While our dataset provides valuable insights, it's essential to acknowledge its limitations. One limitation is that the dataset is not as big as I'd like, but many of the rows had to be dropped as they were duplicated and/or had missing values in important columns. Additionally, the dataset may not capture all cultural nuances that could influence a movie's success, introducing potential biases.
##  Data Analysis
* Action-themed movies dominate the list of highest-grossing films, showcasing the enduring popularity of this genre.
* The number of movie releases steadily increases per season or quarter, suggesting a seasonal influence on the movie industry.
* A film's success can be greatly impacted by knowing audience preferences, maximizing release dates, and carefully controlling production costs. 
## Code Quality
The code in the notebook subscribes to Pep 8 standards. The code has been shortened by use of loops and functions.
## Installation
- Clone the repository:
  ```bash
  git clone https://github.com/maina-leon/Movie_Industry_Analysis





## Usage
- Run the Movie-Analysis notebook:
  ```bash
  jupyter notebook Movie_Industry_Analysis.ipynb
## Contributing
Contributions are welcome! Please follow these guidelines:
- Fork the repository
- Create a new branch
- Make your changes
- Submit a pull request

## Authors

- [@LeonMaina](https://www.github.com/maina-leon)


