# MKT-data-analysis-project
The project aims to analyze advertising expenditure data and its return on sales from leads, in order to better understand the relationship between the variables present in this data and identify the factors that most impact lead generation. Furthermore, the project aims to create a value prediction model to estimate the return on sales that can be generated from a given investment in advertising.
The first step is explore the information on the variables present in the dataset to identify possible inconsistencies, such as missing values, duplicate data or outliers.
After ensuring the completeness of the dataset and making possible corrections, it is necessary to carry out a descriptive analysis to better understand variables and identify problems.

The table of the Descriptive analysis of the dataset:
![image](https://github.com/user-attachments/assets/7cc04467-f5bb-4863-be9a-09c2722599ec)

The descriptive statistics provide insights such as the mean, standard deviation, minimum, and maximum values for each of these columns, which can help in understanding the distribution and range of the data.


With this statistics, it is possible to carry out a exploratory data analysis (EDA) to identify relationships between variables and discover relevant patterns. Using data visualization techniques and statistical analysis, searching for possible correlations and identification of outliers or deviations from normality.

The charts of the EDA:
1. Correlation Heatmap
![image](https://github.com/user-attachments/assets/a9bade7d-bebe-47b4-aceb-34108973c941)


2. Sales Distribution
![image](https://github.com/user-attachments/assets/71a2b21a-0fe8-4b7b-a677-a5b52f4e6c76)


3. Pairplot of Variable
![image](https://github.com/user-attachments/assets/c2b86465-8859-428c-a274-db0807dc9e54)

With the in-depth analyzes carried out, which managed to extract valuable information from the data, it will be possible to build a linear regression model to carry out subsequent prediction.
The regression model has been successfully built and evaluated. The results indicate a Mean Squared Error (MSE) of approximately 5.58 and an R² Score of about 0.87. This suggests that the model explains a significant portion of the variance in sales based on advertising investments, indicating a good fit.

Here are the evaluation metrics:

Mean Squared Error: 5.576790234026713

R² Score: 0.872863085701216

The R² Score of 0.87 indicates that around 87% of the variability in sales can be explained by the model, which is quite strong.

Now the next and final step is to apply the constructed regression model, to predict the return on sales that can be generated from a certain investment in advertising, so that we can complete the project successfully.

Apllying the linear regression model, to make predictions based on specified advertising investments in YouTube, Facebook, and newspapers. The results indicate the predicted sales for each set of investments. And here are the predictions:
![image](https://github.com/user-attachments/assets/f40a5b7d-831c-4976-81ba-e1324788eea2)

With these results we can draw some insights:

1. **YouTube Advertising Influence**: There is a general positive correlation between YouTube advertising and predicted sales. For example:
   - A $200 investment on YouTube leads to predicted sales of around 18.37.
   - A $300 investment on YouTube generates a higher predicted sales return of around 24.73.

   This suggests that increasing spending on YouTube significantly impacts sales.

2. **Facebook Advertising's Moderate Influence**: The Facebook advertising amounts in this dataset vary slightly (30, 25, and 40), but it seems to have a relatively less significant impact compared to YouTube:
   - The highest Facebook spend (40) coincides with the highest predicted sales (24.73).
   - However, even with a slight reduction in Facebook spending, predicted sales aren't affected as drastically, indicating that Facebook may play a supporting but not decisive role.

3. **Newspaper Advertising's Limited Impact**: The spending on newspaper advertising decreases across the rows (20, 15, 10), but the predicted sales don't seem as sensitive to this change:
   - In fact, despite spending less on newspaper advertising, the predicted sales increase, suggesting that newspaper ads may not be as effective in driving sales compared to other channels.

4. **General Trend**: The most significant driver of sales in this dataset appears to be YouTube advertising, with some contribution from Facebook, while newspaper advertising shows limited effectiveness.

### Conclusion:

- Increasing YouTube ad spend has the most noticeable impact on predicted sales.
- Facebook ads may contribute to a moderate boost in sales but aren't as impactful as YouTube.
- Newspaper ads seem to have a minimal influence on sales outcomes.
  
**Strategic Recommendation**: The company should prioritize YouTube advertising for maximum sales returns, consider maintaining or adjusting Facebook spend depending on budget, and potentially reduce investment in newspaper advertising, given its limited influence in this data.
