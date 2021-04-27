# Analyzing Toronto Businesses on Yelp (Python)

Yelp is company that publishes Yelp.com, a website dedicated to crowd-sourced reviews about businesses. Yelp has many key features that help users consume products and services in the most effective way possible. The website and mobile application contains information regarding location (street, city, state/province, country, latitude, longitude), opening and closing hours, services provided, number of reviews, average reviews, business attributes (e.g. accepts credit cards), and taggable categories (e.g. restaurant, health & medical, good for kids, etc.).

In the first iteration of this project, I look to identify a statistical relationship between location and review count against number of stars (out of 5.0, with 5.0 being the best). More specifically, I examine businesses from Toronto (nominal categorical variables) and look to determine whether the number of reviews (discrete variable) has any predictive power when it comes to number of stars given to a business (ordinal categorical variable). This data exploration includes summary statistics, a stacked bar chart, a histogram, a set of boxplots, and two sets of maps.

In the second iteration of this project, I improve upon the data exploration of the first draft by fine-tuning the plots from the first iteration, including a draft of a data visualization stratifying the Yelp data by city wards, and adding three new maps, including an interactive one shown below. I conclude by discussing some limitations of this work and how future projects may use and improve upon this notebook.

In the third iteration of this project, I incorporate webscraped population data and ward-based socioeconomic data to the analysis. I walk through the gathering of the webscraped data and include six new figures as well.

In the final iteration of this project, I run four regressions and create a regression tree for my variables of interest. I reformulate the introduction to include a brief literature review and expand upon the findings, limitations, and extensions of this work.

An updated version of the data used in this project can be found at https://www.kaggle.com/yelp-dataset/yelp-dataset.
