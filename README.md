# Suicide Rates Overview (1985-2016)

# Dataset & History
  from Kaggle: https://www.kaggle.com/code/hecshzye/suicide-rate-eda/data

# Analysing & Predicting Suicide Rates Around The Globe
- The objective of this model is to predict the rate of suicide.
- Following the Exploratory Data Analysis, we will be using Regression models to predict.
- This compiled dataset pulled from four other datasets linked by time and place, and was built to find signals correlated to increased suicide rates among different cohorts globally, across the socio-economic spectrum.

# References
- United Nations Development Program (2018). Human development index (HDI). fRetrieved from http://hdr.undp.org/en/indicators/137506

- World Bank (2018). World development indicators: GDP (current US$) by country:1985 to 2016. 
- Retrieved from http://databank.worldbank.org/data/source/world-development-indicators 
- Suicide in the Twenty-First Century [dataset]. 
- Retrieved from https://www.kaggle.com/szamil/suicide-in-the-twenty-first-century/notebook 
- World Health Organization (2018). 
- Suicide prevention. Retrieved from http://www.who.int/mental_health/suicide-prevention/en/

# Bigger Picture & Objective
- Our unified effort to prevent suicide & loss of meaning in one's life.
- We have two ways to look at life: Optimistically/Pessimistically & Nihilistically.
- No one knows the meaning of life & the existential question is an open one.
- We can either be happy & cool about not knowing anything or unhappy about not knowing anything.
- Finding ways to cultivate cooperation & empathy among the population is necessary.
- If you know someone around you or close to you going through a difficult time, please reach out & be present.
- I hope you are okay.



Don't give up. The darkest night is just before dawn.

You'll never know what would've happened if you stuck it out & push through it.

The process shapes you before success rewards you.

Be strong.

I'm proud of you for making it this far. Let's keep going! ❤️ 🔥

![FK0WbN4UUAU0NYR](https://user-images.githubusercontent.com/87764103/159164659-be9940a9-cb6b-4e94-a891-d3622f0d9e4e.jpeg)


# Exploratory Data Analysis

## Model using Linear Regression

![download](https://user-images.githubusercontent.com/87764103/159251403-9790a682-e0f1-45f3-890e-2a670370948f.png)

**Model using Random Forest Regressor

![download (1)](https://user-images.githubusercontent.com/87764103/159255814-6025859b-fd3b-4177-bac5-70f35b514415.png)


# Conclusion

## model_1 with Linear Regression

  - accuracy : 46.9%
  - MSE : 373662.16998576623
  - r2 : 0.49408809317334645
  - RMSE : 611.2791260837935
  
## model_2 with Random Forest Regression

  - accuracy : 99.925%
  - MSE : 5814.208211125089
  - r2 Score: 0.007688043583478188
  - RMSE: 76.25095547680101
  
## model_3 with Random Forest Regression (without "HDI for year" column)

  - accuracy : 99.930%
  - MSE : 5649.7600005391805
  - r2 Score: 0.007470596088600012
  - RMSE: 75.16488542224475
  
  
## Note: The dataset isn't great observing that it is incomplete & about 70% data missing in the "HDI for year" column which is crucial for predicting suicide rate by analyzing the "Human Development Index for a year" which could be a major attribute when predicting the overall development index of a country
