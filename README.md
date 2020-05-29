# Data Analysis Portfolio by Juliann Nguyen

This portfolio is a compilation of some of my favorite projects that I've worked on that showcase some of the skills that I've developed using python, R, and excel. 

## Course Projects

#### [Bike Sharing Predictions and Inference](https://github.com/juliannnguyen/juliann.portfolio/blob/master/Files/Bike_Sharing_Predictions_and_Inference.pdf)
Using bike sharing datasets in Washington D.C., Chicago, and New York, I did some exploratory data analysis on the different features and ran different machine learning algorithms to make predictions on which trips were from registered or casual riders. The first method, I explored was to fit a logistic regression model and used the Benjamin Hochberg procedure to make predictions that ensured that false positive rates were controlled. The second method was to fit a gaussian mixture model in hopes of increasing sensitivity in the predictions. I then used a 2 stage least squares model to try to answer the question of what impact weather has on the number of rentals, since weather and the number of rentals were both highly correlated with temperature, using 2 stage least squares would help control for this confounding variable and allow for the possibility of causal inference. 

#### [Clothing Classification using Photos](https://github.com/juliannnguyen/juliann.portfolio/blob/master/Files/Clothing_Classification_using_Photos.pdf)
Using a dataset of photos of different articles of clothing, I used principal component analysis for dimension reduction, then used various classification models to classify the articles of clothing using the lower dimensional photos. Some of the classification methods utilized were logistic regression, linear discriminant analysis, quadratic discrimant analysis, and k nearest neighbors using binary models and also multiclass models. 

#### [Predicting Violet Crimes](https://github.com/juliannnguyen/juliann.portfolio/blob/master/Files/Predicting_Violent_Crimes.pdf)
The crime and communities dataset contains crime data from communities in the United States. There are over a hundred different attributes and the goal was to predict the total number of violent crimes per 100K popuation. I utilized LASSO as a dimension reduction technique and modeled the data using several methods such as linear regression, a decision tree, and random forests to find the most accurate model. 

#### [Predicting the Number of Bike Sharing Rentals Strictly using Linear Methods](https://github.com/juliannnguyen/juliann.portfolio/blob/master/Files/Predicting_the_Number_of_Bike_Rentals_Linear.pdf)
Linear models are often less computationally expensive and also are usually easily interpretable for predictions or summarizing relationships. In this project, I utilized data from Capital Bikeshare System to predict the number of rentals for a given hour using linear models and techniques such as exhausitve feature selection with adjusted R2, ridge regression, lasso regression, and cross validation to find the best model for the problem. 

#### [Microclimates in Redwoods](https://github.com/juliannnguyen/juliann.portfolio/blob/master/Files/Microclimates_in_Redwoods.pdf)
Considering the data and research in the paper, [*A macroscope in the redwoods*](https://dl.acm.org/doi/10.1145/1098918.1098925), a partner and I explored the findings in the paper and our findings with the data using different visualizations to better show the microclimate of coastal redwood trees, principal component analysis for feature reduction, and kmeans clustering and gaussian mixture models to predict the method in which the data was collected. 

#### [Maximizing Flyering](https://github.com/juliannnguyen/juliann.portfolio/blob/master/Files/Maximizing_Flyering.pdf)
Interpreting the problem of maximizing the number of flyers as a multi armed bandit problem and using trip counts from different city stations, I ran simulations of this problem to find the results and implications of using the upper confidence bound algorithm for selection of the street corner and discussed the assumptions and conditions of the original problem of maximizing the number of flyers being considered as a multi armed bandit problem. 

#### [Privacy Concerns](https://github.com/juliannnguyen/juliann.portfolio/blob/master/Files/Privacy_Concerns.pdf)
Since datasets are sometimes released to the public, the combination of these datasets could lead to the identification of some individuals. Using scooter data from Berkeley and some statistical methods, I explored how some individuals could be identified and connected to their specific scooter rental rides given relatively general information. 

#### [Exploring Amazon's Impact on Seattle](https://www.ocf.berkeley.edu/~juliannnguyen/)
In an urban data analytics course, a partner and I decided to analyze the impact that Amazon had on the city of Seattle when building its headquarters there using census and real estate data. Using excel and the geopandas library in python, we created graphs, maps, and tables to help summarize and showcase our findings. 
