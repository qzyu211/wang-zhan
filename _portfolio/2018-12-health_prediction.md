---
title: "Low Birthweight and Heart Disease Prediction Analytics"
excerpt: "The final project for the Analysis of Categorical Data (STA 138) course, utilizing logistic regression and Poisson regression."
header:
#  image: /images/lda_plot_nut_proj.JPG
  teaser: /images/plots_health_proj.JPG
#sidebar:
#  - title: "Multivariate Data Analysis Final Project"
    #image: http://placehold.it/350x250
    #image_alt: "logo"
  #  text: "Individual work, grade earned: A"
  #- title: "Responsibilities"
  #  text: "Reuters try PR stupid commenters should isn't a business model"
gallery:
  - url: /images/plots_health_proj.JPG
    image_path: /images/plots_health_proj.JPG
    alt: "Exploratory plots to visualize the data with transformations."
  - url: /images/residuals_health_proj.JPG
    image_path: /images/residuals_health_proj.JPG
    alt: "Analysis of different residuals."
  - url: /images/coef_health_proj.JPG
    image_path: /images/coef_health_proj.JPG
    alt: "Resulting prediction of coefficients."
---
Two different datasets were studied in the final project for an Analysis of Categorical Data (STA 138) course at the University of California, Davis with Prof. Burman. The first dataset consisted of predictors and a binary response variable. The second dataset consisted of predictors and a count response variable. The former was modeled using Logistic Regression, and the latter was modeled using Poisson Regression. Different statistical summaries were performed on both datasets, along with an analysis of which variables would be best suited to be used as predictors. Scatter plots and box plots were used to analyze relationships between possible predictors and the response variables. Goodness-of-Fit tests were done using the Likelihood Ratio statistic. Backward Stepwise Regression was the primary tool for selecting a final model, utilizing the AIC criterion as the metric. Residuals were calculated using deviance and Pearson residuals, including their standardized versions. An analysis of the final model consisted of examining the final predictors and the interaction terms in relation to the variable definitions given through the dataset. The final part of the report consisted of a discussion of the main points such as possible assumption violations and data errors, and a conclusion on what sort of possible steps could be taken if there were more available time. This last part included the possibility that a certain model was not appropriate for the data, given assumptions that the model is based upon.

{% include gallery caption="Plots from the project include (1) exploratory plots to visualize the data with transformations, (2) analysis of different residuals, (3) resulting prediction of coefficients." %}
