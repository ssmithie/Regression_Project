# Regression_Project
This project will take a look at the BeerAdvocate (BA) score for beers and perform regression analysis to determine what factors affect the score, and then build a model that can accurately predict the score given those parameters.

## Data Collection
We used the [BreweryDB](https://www.brewerydb.com) API to take a random sample of 1,000 beers from accross the world.
We then used both selenium and beautiful soup to search [BeerAdvocate](https://www.beeradvocate.com) for each of those beer and pull the following information for them: BA score, user rating, ABV, style, brewery location, beer availability.

## Data Cleaning
We chose to drop the 10% of our data that had no BA score, and categorized the beer styles and brewery location.
We then turned our 3 categorical variables (region, style, availability) into dummy variables.
