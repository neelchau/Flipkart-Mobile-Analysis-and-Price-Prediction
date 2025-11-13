Flipkart Mobile Sales Analysis
Project Overview
This project aims to analyze mobile phone sales data from Flipkart to understand various trends, distributions, and relationships between different attributes of mobile phones. Additionally, a Linear Regression model is built to predict the selling price of mobile phones based on their features.

Dataset
The analysis uses the Flipkart_Mobiles.csv dataset, which contains information about mobile phones, including Brand, Model, Color, Memory, Storage, Rating, Selling Price, and Original Price.

Exploratory Data Analysis (EDA)
The following key aspects were explored through visualizations:

Scatter Plot for Original Vs Selling Price: Visualizing the relationship between the original and selling prices of mobile phones.
Distribution of Ratings: A histogram showing the frequency distribution of mobile phone ratings.
Box Plot for Distribution of Ratings By Brand: Understanding the rating distribution across different brands.
Violin Plot for Distribution of Ratings By Brand: A more detailed view of the rating distribution and density for each brand.
Distribution of Rating for Samsung Brand: A specific histogram to analyze the ratings of the most selling brand (Samsung).
Pie Chart for Most Selling Phones: Visualizing the market share of top brands and others.
Bar Graph for Number of Models By Brands: Counting the unique number of models offered by each brand.
Top 10 Models: Identifying the most frequently appearing models in the dataset.
Bar Graph for Most Selling Color: Showing the distribution of the top 5 most common phone colors.
Count of Selling of Phones By Brands: A bar plot displaying the total number of phones sold by each brand.
Average Selling Price By Brand: Highlighting the average selling price for each brand.
Number of Phones Available in different Price Ranges: Categorizing phones into 'Low Range', 'Mid Range', and 'Premium Range' and showing their counts.
Most Costly Selling Models: Identifying the most expensive model for the top 10 brands.
Selling Price and Rating for Phones: A scatter plot to observe the relationship between ratings and selling prices, categorized by brand.
Predictive Modeling
A Linear Regression model was implemented to predict the Selling Price of mobile phones.

Data Preprocessing:
Missing values in the 'Rating' column were imputed.
Categorical features (Brand, Model, Color, Memory, Storage, Price Range) were encoded using LabelEncoder.
Numerical features (Original Price, Selling Price) were scaled using StandardScaler.
Rows with any remaining NaN values were dropped before training.
Model Training and Evaluation:
The data was split into training and testing sets (80% train, 20% test).
A LinearRegression model was trained on the preprocessed data.
The model achieved an R2 Score of 97.16%.
A scatter plot comparing actual vs. predicted selling prices demonstrates the model's performance.
