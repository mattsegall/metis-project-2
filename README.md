# Wine While Blind (?)

### Description

With around 100,000 wine producers throughout the world, each likley representing at least a dozen varities, the process of choosing a good bottle can feel overwhelming. As a wine fan, I'd like to arm myself with some useful information on choosing a great bottle for future visits to the wine shop. I can achieve this by processing wine review data through a linear regression, and observing which attributes seem to be associated with an increase in review score. For example, wines from France might show quite a high positive coefficient, in which case I'd target French wines in future trips. Or, perhaps wine of a certain style or grape (Manischewitz?) may show a negative coefficient, in which case I would consider avoiding. 

### Features and target vairables

My target variable is average review score on Vivino. My features will be various attributes about the wine like:

* producer
* style
* geographic origin (country, region)
* average bottle price
* popularity/availabilty (via # of reviews)
* varietals present (types of grapes)
* presence of sulfites or other preservatives

### Data Used

I wil primarily use data scraped from Vivino, perhaps supplementing with one of the many wine review data seta available online. I may bring in other data sources to aid in more interesting insights, like climate and soil types.

### Tools Used

* BeautifulSoup
* Selenium
* Pandas
* Numpy
* Scikit-learn
* Statamodels

### Possible Impacts

To all be more educated wine drinkers and buyers, and spend on hard-earned dollars on better wines for any budget!