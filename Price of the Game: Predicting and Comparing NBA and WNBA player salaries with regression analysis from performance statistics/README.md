### Price of the Game: Predicting and Comparing NBA and WNBA player salaries with regression analysis from performance statistics

**Overview**

In this project, my partner Anna Salam and I sought out to compare the predicitive analysis methods for salaries of individuals in the NBA and WNBA, respectively. 

We hypothesized that WNBA players’ salaries are highly correlated with FG% because society rewards perfection from women. NBA players’ salaries are highly correlated with minutes played because pay is often dependent on media coverage and viewership.

**Data Collection**

We used the BeautifulSoup package to scrape data from a number of publicly available websites:

- NBA Performance Data:       www.cbssports.com
- WNBA Performance Data:      www.espn.com
- NBA Salary Data:            www.espn.com
- WNBA Salary Data:           www.spotrac.com

We then added our data to a CSV file, where we proceeded to clean the data in Excel. For the most part, the data did not seem to have a lot of errors or holes.

**Variables of Analysis**

Variables compiled in data scraping for both NBA and WNBA players for the 2021-2022 season:

- Average Minutes Per Game
- Average Points Per Game
- Field Goal Percentage
- Proportion of Games Started
- Salary (USD)
- Total Minutes (Not used in regression)
- Total Points (Not used in regression)

**Methods of Analysis**

For both NBA and WNBA players, we chose to implement a regression as a predictive method for salaries, based on performance data.

We tested a variety of different regressions available in the SKLearn package in Python, including Linear, Ridge, Tweedie Regressor, Lasso, Lasso Lars, and Elastic. We found that the Linear regression had a [marginally] higher score in training and testing some of the data, so we ultiamtely chose Linear regression for our predictive analysis for both NBA and WNBA players.

_For regression results, please refer to the Final Presentation.pdf file available in this folder._

**Available to View in this Folder**

We have provided the code to both our data collection methods and regression methods for both NBA and WNBA players in this folder. This code was written in Java via Jupyter Notebooks. 

We have also provided the (previously mentioned) Final Presentation to reference the final results and discussion as to unexpected results/what we could have done better, as well as the final CSV's we used to run our regressions.

