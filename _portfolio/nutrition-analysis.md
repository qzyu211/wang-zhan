---
title: "Nutrition Analysis"
excerpt: "The final project for the Multivariate Data Analysis course (STA 135) at U.C. Davis."
header:
  image: /images/lda_plot_nut_proj.JPG
  teaser: /images/lda_plot_nut_proj.JPG
#sidebar:
#  - title: "Role"
#    image: http://placehold.it/350x250
#    image_alt: "logo"
#    text: "Designer, Front-End Developer"
#  - title: "Responsibilities"
#    text: "Reuters try PR stupid commenters should isn't a business model"
gallery:
  - url: /images/scree_plot_nut_proj.JPG
    image_path: /images/scree_plot_nut_proj.JPG
    alt: "Scree plot and proportion of variance plot."
  - url: /images/beef_vege_biplot_nut_proj.JPG
    image_path: /images/beef_vege_biplot_nut_proj.JPG
    alt: "Biplot of beef and vegetable data."
  - url: /images/lda_hist_nut_proj.JPG
    image_path: /images/lda_hist_nut_proj.JPG
    alt: "Stacked histogram of the LDA values for the beef and vegetable groups."
---
This was an individual project for the Multivariate Data Analysis (STA 135) class from the University of California, Davis with Prof. Li. The programming analysis was done using R. In the project, a nutritional dataset selected from online with thousands of observations divided into various food groups was utilized. Each observation consisted of columns that described the various nutrient contents for 100 grams of a given food (e.g., Australian Wagyu Steak, grilled beef patty, etc.). Then performed multivariate analysis comparing the food groups beef and vegetable products. The different methods included simultaneous confident intervals using Hotelling’s T-squared and Bonferroni’s corrected method, Hotelling’s two-sample test, principal component analysis (PCA), and linear discriminant analysis (PCA). The analysis was compiled into a report that summarized the data, described the process of analysis, along with interpretations and conclusions of the results.

{% include gallery caption="Plots from the project include (1) Scree plot and proportion of variance plot, (2) Biplot of beef and vegetable data, (3) Stacked histogram of the LDA values for the beef and vegetable groups." %}
