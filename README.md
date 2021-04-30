# McDonalds_EDA
Project 2: Whats on The Dollar Menue?

Exploratory Data Analysis on McDonald's Data.

Questions:

How many calories does the average McDonald's value meal contain?
How much do beverages, like soda or coffee, contribute to the overall caloric intake?
Does ordering grilled chicken instead of crispy increase a sandwich's nutritional value?
Data:

This dataset provides a nutrition analysis of every menu item on the US McDonald's menu, including breakfast, beef burgers, chicken and fish sandwiches, fries, salads, soda, coffee and tea, milkshakes, and desserts. The menu items and nutrition facts were scraped from the McDonald's website.

Methods:

Group data by category to get summarizations for graphics and reorder levels to make data more presentable. Filter through data to find Category for Chicken and remove observations that are not grilled or crispy chicken sandwiches such as, removing Filet-O-Fish and Nuggets. Then search through strings to find keyword Grilled, then creating a new variable type with value Grilled if a string contains word Grilled else Crispy. Used t-tests to compare grilled versus crispy chicken means for calories, protein, and total fat. Used t-tests to compare grilled versus crispy chicken means for calories, protein, and total fat. The results of the t-tests show that there is no significant mean difference between the mean calories for grilled and crispy chicken sandwiches. There is a significant mean difference between the protein of crispy and grilled chicken sandwiches. There is a significant mean difference between total fat daily % of crispy and grilled chicken sandwiches. I used ggplot2 to graph the data to make it presentable and understandable to interested parties.

Since there is no difference in calories between crispy and grilled chicken on average, we are worried about protein and total fat. From the t-tests, we can see grilled chicken has more protein on average and less total fat, so we can conclude that grilled chicken increases a sandwich's nutritional value.
Results:

Limitations and Next Steps:

The graphs can be improved using shiny to make an interactive dashboard, which can boost the interpretability of the findings to interested parties.
