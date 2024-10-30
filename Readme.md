# Project Name
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.

A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. BoomBikes aspires to understand the demand for shared bikes among the people after the ongoing quarantine situation ends across the nation due to Covid-19. *They want to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.* 

The company wants to know:
- Which variables are significant in predicting the demand for shared bikes?
- How well those variables describe the bike demands?

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
> A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. BoomBikes aspires to understand the demand for shared bikes among the people after the ongoing quarantine situation ends across the nation due to Covid-19. *They want to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.* 
- What is the background of your project?
> Its done as part of IIITB Executive PG Machine Learning Course 1 - Linear Regression.
- What is the business probem that your project is trying to solve? 
> In this assignment, model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- What is the dataset that is being used? 
> day.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We can see our best fitted line to be :
$$cnt = 0.2*const + 0.23*yr + 0.047*workingday + 0.46*atemp - 0.088*hum - 0.11*season\_spring $$
$$+ 0.073*season\_winter - 0.04*mnth\_jan - 0.06*mnth\_nov + 0.07*mnth\_sep - 0.05*weathersit\_cloudy$$ 
$$- 0.246*weathersit\_lightRain$$

The above variables are significant with an adjusted r-squared value of **0.837**. It has Prob (F-statistic) equal to 5.65e-186 which implies that the fitted line is significant.

After running the model through the test data set, we get a r-squared value of **0.79** which is close to our training R-Squared. It shows that our model is generic enough.
## Technologies Used
- Python, Jupyter, Pandas, Numpy, matplotlib, seaborn, sklearn, statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upGrad IIITB ML & AI PGDM programme.
- This project was based on Multiple Linear Regression.


## Contact
Created by [@Shaily20] - feel free to contact me!
