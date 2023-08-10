# Project1

Introduction
​
The purpose of this project is to gain insights into the factors that contribute to videos receiving over 10,000 views on YouTube and engaging a more active audience. By analyzing randomly sampled videos with views exceeding this threshold, we aim to understand the relationships between various metrics such as view counts, likes, dislikes, comments, and video category.
​
Methodology
​
Data Collection
We utilized the YouTube Data API v3 to retrieve essential information about videos, including their view count, likes, dislikes, comments, and content category. Due to the random nature of the data obtained from the API (especially without specific search keywords), each team member independently extracted video data and exported it as a CSV file. Despite the variability in the datasets, we all followed the same code to obtain the data frames from the API.
​
Data Cleaning and Merging
To ensure consistency and comparability across our analyses, we meticulously cleaned the individual CSV files. Duplicated data was identified and eliminated, which involved a dedicated code segment for data cleanup. We purposefully separated the code for API data retrieval, data cleanup, and data visualization to address any potential issues arising from future changes in the dataset.
​
Data Visualization
The cleaned and merged dataset enabled us to perform thorough data analysis and visualization. We plotted scatter plots to visualize relationships between various metrics such as likes, views, and comments. Additionally, we conducted linear regression analysis to understand potential correlations between these metrics. We ensured that the visualizations were insightful and accurately conveyed the underlying patterns in the data.we have plotted bar plots to determine the the relation of comments and views againt the differnt categoies of videos in the cleaned dataset also to determine if comments and views have any corelation
​
Repository Structure
​
The repository is organized as follows:
​
Resources/: Contains the individual CSV files exported by each team member from the YouTube Data API.
output/: Stores the generated plots and visualizations.
API-code.ipynb, data-clean-up-code.ipynb: Jupyter Notebook containing the code for data retrieval, cleaning.
