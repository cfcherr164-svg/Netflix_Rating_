# Netflix Exploratory Data Analysis (EDA): Content Ratings and Content Types

This project explores the relationship between content ratings and content types available on Netflix using the Netflix Titles dataset. The main objective is to identify the distribution of Movies and TV Shows and examine how content ratings vary between these two categories. In addition, the analysis aims to determine which ratings are the most common across Netflix's library.

The analysis was conducted using Python with the pandas and matplotlib libraries. First, the dataset was loaded and inspected to understand its structure and identify missing values. Since the focus of this project is on the relationship between content type and rating, only the "type" and "rating" columns were selected for further analysis. Missing values were removed to ensure the accuracy of the results.

After cleaning the data, a cross-tabulation method was used to count the number of Movies and TV Shows for each rating category. The results were then visualized using a bar chart, making it easier to compare the distribution of ratings between the two content types. An additional chart showing the overall proportion of Movies and TV Shows can also provide a clearer overview of Netflix's content library.

The findings indicate that TV-MA and TV-14 are the most common ratings on Netflix. These categories contain the largest number of titles for both Movies and TV Shows. The analysis also shows that Movies generally outnumber TV Shows across most rating categories, suggesting that Netflix offers a larger selection of films than television series.

In conclusion, this project demonstrates how simple exploratory data analysis techniques can reveal useful patterns within a dataset. By applying basic data cleaning, grouping, and visualization methods, the relationship between Netflix content ratings and content types becomes easier to understand. The results provide a general overview of Netflix's content distribution and illustrate the usefulness of EDA in summarizing and interpreting real-world data.
