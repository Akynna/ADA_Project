# Tell me what you eat, I'll tell you where you're from



Data Story of the project : https://avadarteam.github.io/



# Abstract

Each country has its own historical experience that has shaped its culture over the time. During this process, the food culture has also evolved differently in each part of the world, and regions have created and developed their affinity with certain food.

In this project, we want to highlight the food trend in each country and to realize their relation with the culture of the country. To this end, we have decided to use the _Open Food Facts_ dataset, which will allow us to make those observations.

It might be interesting to see which kind of food is more sold and consumed in a country and to see if this is related to the country culture. These information can be then useful for people who like to travel and can help them to better understand the culture of each part of the world.


# Research questions

- What type of food is eaten in which country?
- Do we see a correlation between the nutriments eaten in a country and the country itself?
- More precisely, is there a link between the food specialties in a country and its culture ?
- Is there a geographical interpretation of the kind of nutriments consumed in certain regions ?
- If we go deeper, does the type of food influence population's health ?

# Dataset

We will use the `Open Food Facts` dataset. The dataset is in CSV format and is not too big (1.6Gb), so it will be fine to work on it, using only Pandas (with a larger dataset it would have been more convenient to use Spark). We have chosen to use only Pandas because it is very powerful and it might help us to do everything we want.

The dataset consists of multiple information about food products, as for example the name of products, the ingredients, the countries in which those products are sold and the nutrition properties of the product such as the sugar, the energy and so on.

We will try to extract some useful information about what people eat in the different regions of the world and what are the main nutrition elements they eat. We want to see if there is a correlation between the food and the location. This could be useful to orient the tourists on what to eat in which country.


# A list of internal milestones up until project milestone 2

## 1. Think about the available data we have & how to visualize it (until Nov. 11th)
- Look for other dataset/table that can help us to highlight our future observations and give more meaning to our results
- Preprocessing : find a way to load the data on our computer
- Think about ways to visualize / tell the story of our data and see what can be shown


## 2. Work on the cleaning and transformation of the dataset (until Nov. 18th)
- Study more deeply available data and extract the first useful information and attributes we want to observe
- Make a list of our expectations concerning the results
- Plot the first results and find the first most significant representations


## 3. Work on notebook and visualizations (until Nov. 25th)
- Write the process text and work on relevant commented notebook that can be read by other people
- Have nice visualizations and first results in notebook
- Find the relation between the results and our assumptions

# Questions for TAs

Here are some questions we had when writing the milestone 1. More might come during the process of our project:
- How do we do if we can't find relevant observations on our data?
- How complex must be our analysis of the dataset?
- Can we have a list of points that we have to satisfy in order to know if we are going in the right direction?
