# About the project

> This project seeks to understand food security challenges around the world. Using publicly available data aggregated from multiple sources, I conducted a range of statistical and machine learning analyses to draw insights about where countries are in terms of their ability to meet food demand, what factors affect food security levels, and how we can create resource-efficient and climate-resilient food systems to sustain current and future generations.
>
> See my [Medium article](https://medium.com/@mailan_HOANG/future-of-food-how-to-meet-the-challenge-of-feeding-more-with-less-9dbbb2a7c7d) for more detailed write-up.

# Data

> I used the following data sources to create an aggregated dataset covering over 200 countries and territories.
>
> -   Prevalence of food insecurity --- Food and Agriculture Organization (FAO)
>
> -   Population data --- Food and Agriculture Organization (FAO)
>
> -   Agriculture land per capita --- Food and Agriculture Organization (FAO)
>
> -   Agriculture productivity --- World Bank
>
> -   GDP per capita --- World Bank
>
> -   Digital adoption --- World Bank
>
> -   Political stability --- World Bank
>
> -   Climate risk --- Germanwatch

> The combined clean dataset is shared on this GitHub repository.

# Analyses

**Model Development**

There are three parts to my analyses:

-   **Clustering model**. Hierarchical clustering was used to identify "natural groups" of countries and understand the characteristics they might have in common or where they differ.
-   **Linear regression model.** Linear regression was used to predict the prevalence of food insecurity. Correlations between independent variables were calculated and some variables were removed to avoid multicolinearity issues. Based on the results of the model, I identified significant predictors and interpreted their impact on countries' food security.
-   **Regression tree model**. Regression tree was also used to predict the prevalence of food insecurity. A minimum bucket size of 10 was selected to avoid "over-fitting".

**Model Evaluation**

I evaluated the models based on their performance on the testing set obtained by randomly splitting the original dataset. Both linear regression and regression tree models performed relatively well with high testing R Squared.

One limitation of these analyses is the small sample size. However, since the project's main focus is on the interpretation of the variables and their impact on food security, the models did provide valuable insights and are well aligned with findings of existing literature.

# Get in touch

> [\@Email](mailan.mlh@gmail.com)

> [\@LinkedIn](https://www.linkedin.com/in/mailan-hoang/)
