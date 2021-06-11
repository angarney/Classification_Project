# Classification Project

[Maker Megan](https://makermegan.com/) is a local business looking to increase the sales conversation from her e-commerce platform. Data from Maker Megan's website were explored to create a logistic regression. Findings from this analysis show one of the largest factors influencing Maker Megan's conversation rate is her checkout experience. Some factors additional positive influences include customers accessing on the weekend and from the US. A few negative infuences were found. Some of these include accessing the page initially through Maker Megan's home or collections pages. Moving forward Maker Megan should:
* Keep the checkout experience the same
* Re-evaluate the current product organization
* Focus additional marketing efforts on the weekend

The project workflow and model building code can be found [here](https://github.com/angarney/Classification_Project/blob/main/Project%20Development/maker_megan_workflow.ipynb).

## Design
Maker Megan website behavior data were explored look at opportunities to increase the sales conversion rate. 
* **Opportunity:** Maker Megan is hoping to increase sales as she transitions from building to growing the business in her second year. 
* **Impact:** Increase sales conversion rate on e-commerce platform
* **Data Science Solution Path:** Logistic Regression Classification Model
* **Impact Hypothesis:** Getting of better understanding of factors website predicting purchasing behavior will allow Megan to increase the sales conversation rate. 

## Data

~23,000 data were obtained from Maker Megan. 

**Maker Megan Features:** ua browser version, ua browser, ua form factor, ua os version, ua os, page path, page resource id, page type, page url, location city, location region, location country, referrer host, referrer name, referrer path, referrer source, referrer url, hour, day, week, month, quarter, year, hour day, day name, month name, visitors, sessions, avg duration, bounce rate, item in cart, reached checkout, purchased item, total page views

## Algorithms
**Feature Engineering:** Several features were added such as season, weekday/weekend, US/international, Instagram/other browser. 

**Model Selection and Evaluation:** A logistic regresssion was selected for interpretability. When evaluating models, the F1 score was used as it was important look at both recall and precision. 

**Model Building:** Hyperparameters were tuned using grid search.

## Tools
* [Pandas]()/[Numpy](): Data cleaning/merging and exploratory data analysis
* [Seaborn](http://seaborn.pydata.org/index.html)/[Matplotlib](https://matplotlib.org/): Data visualization
* [Scikit-Learn](https://scikit-learn.org/stable/): Classification Modeling

## Communication
Visuals and a [presentation](https://github.com/angarney/Classification_Project/blob/main/Presentation/maker_megan_061121.pdf) were created. 

![barchat](https://github.com/angarney/Classification_Project/blob/main/Visuals/betas_maker_megan.png)