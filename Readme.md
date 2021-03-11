## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The project aims to use three machine learning algorithms to predict vinyl record prices. 
Vinyl record value (especially among collectors) is heavily affected by unquantifiable aspects (collectors' community, scarcity, artists' popularity). For this reason, another aim is to understand which measurable factors impact the value of a record. 

## Hypotheses / Questions
* What measurable features impact the price of a vinyl record?
* How accurately can machine learning algorithms predict value that is quite subjective and heavily impacted by cultural and emotional aspects?

## Dataset
* Data was collected by web scraping a popular vinyl resale marketplace (16,675 observations and 23 features, using Selenium and BeautifulSoup)
* Test data from a real vinyl record store (due to time constraints this part will be conducted after the presentation)

## Cleaning
Python was used for data wrangling

## Analysis
* Exploratory data analysis to understand the data.
* Decided to focus on price ranges $0-100 and $0-60 to train the models on most common prices.
* Applied Linear Regression, K Neighbors Regression and Random Forest Regression.

## Conclusion
* It is possible to predict viny record prices, however the accuracy is better at lower price points and the results of this project would be better applied on estimating the worth of private record collection rather than giving accurate prices.
* Based on my collected dataset, the mist impactful (measurable) features that influence the value are: community rating, community have/want, number of tracks on a record and age

## Future Work
To expand this project, it would make sense to try to quantify 'subjective' features that are really decisive in a record price. E.g. quantify the popularity of an artist by using Spotify API rankings and also find data on the number of units presser per record.

## Links


[Repository](https://github.com/siloik/final_project)  
[Slides](TBA)  