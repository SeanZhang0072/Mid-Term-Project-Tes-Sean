# Mid-Term-Project-Tes-Sean

## Project/Goals
The project focused on analyzing a dataset from Kaggle, which detailed the situation of Airbnb in nine crucial cities in Europe (including some capitals). Our objective was to utilize these data to identify the key variables affecting housing prices, customer satisfaction, attractiveness, and restaurant coefficients. We aimed to visualize this information for clients planning to open Airbnb properties, aiding them in making informed decisions.

## Process
### Step 1: Data Cleaning
The first step involved cleaning the data, and removing any inconsistencies or errors to ensure accurate analysis.
### Step 2: Exploratory Data Analysis (EDA)
We conducted an EDA to understand the data better, and identify trends, patterns, or relationships among the variables.
### Step 3: Encoding String Data
Some of the variables in the dataset were strings. We encoded these string variables for effective regression analysis.
### Step 4: Regression Analysis
We then performed regression analysis to explore the relationships between different variables, especially how they relate to housing prices, customer satisfaction, and other factors of interest.
### Step 5: Data Visualization
The final step involved visualizing our findings using Tableau to present them in a user-friendly and understandable manner.

## Results
1. The most significant factor affecting prices was the city. This might be due to the varying cost of living across different countries.
   ![Alt text](https://drive.google.com/uc?export=view&id=1_1XOarUIP3An_NuoqnTOpFrxN6QnRwm5)
   ![Alt text](https://drive.google.com/uc?export=view&id=1c0bUNF9LvGxaw2BfabdoHgOtDPK6ihDm)
2. There was no apparent correlation between customer satisfaction and price. However, rooms rented by customers with satisfaction levels between 50-65 had relatively higher average prices, possibly due to unmet expectations.
   ![Alt text](https://drive.google.com/uc?export=view&id=1UhG7J4umG38U7nNHxJtUyuTg_dVbf348)
3. The further away from the city center and subway, the greater the negative impact on the price, customer satisfaction, and both indexes.
   ![Alt text](https://drive.google.com/uc?export=view&id=1jp7MyEYwvQTE3SM36BGJLXZjZPdzIDUi)
   ![Alt text](https://drive.google.com/uc?export=view&id=1ABnvnjTM5KfH1a9f3-GYPOB2aB1_YBjg)
   ![Alt text](https://drive.google.com/uc?export=view&id=1ZIbtJwo2paXez_egfzvUuDgKy-0OBRp5)
4. Superhosts had higher average customer satisfaction ratings in every city compared to non-superhosts.
   ![Alt text](https://drive.google.com/uc?export=view&id=1EaEr5TjeVa_n-g6yqrdHGYu_Z5ri6MNM)
5. Customers clearly preferred rooms with high cleanliness.
   ![Alt text](https://drive.google.com/uc?export=view&id=1XZ30I-qErsAqJIOiWE-Q4kN8C2fVUP4i)
   
## Challenges 
1. Initially, we had difficulty achieving a sizable R-squared value in regression. After encoding strings and removing variables with high p-values, we managed to get usable results.
2. Our group was relatively unfamiliar with using GitHub for version control, but this group work served as a great learning experience!
3. We had high expectations for the dataset as it was comprehensive, with little to no missing values or format standardization needed. However, the dataset didn't contain much high correlation information, making our analysis findings somewhat monotonous.
4. The presentation section needs improvement, particularly with time management and the efficiency of PPT presentations.

## Future Goals
1. We hope to apply machine learning algorithms to predict Airbnb prices and customer satisfaction in different cities based on the variables identified in this project.
2. In the future, we would like to examine more diverse datasets, including additional cities, to expand our understanding of global Airbnb trends.
3. As part of our continuous learning process, we plan to enhance our data presentation skills, focusing on creating more engaging and insightful visualizations.
4. Improving our knowledge and usage of version control tools, like GitHub, will be a priority, as it is crucial for seamless collaboration in data science projects.
5. Lastly, we intend to incorporate more external data (like tourism statistics, city population density) to enrich our analysis and yield more nuanced insights.
